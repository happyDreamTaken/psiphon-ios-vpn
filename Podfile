# Uncomment the next line to define a global platform for your project
platform :ios, '10.0'

 # Disable sending stats
ENV['COCOAPODS_DISABLE_STATS'] = 'true'

target 'Psiphon' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  #use_frameworks!

  # Pods for Psiphon
  pod "InAppSettingsKit", :git => "https://github.com/Psiphon-Inc/InAppSettingsKit.git", :commit => '598c498'
  #pod "InAppSettingsKit", :path => "../InAppSettingsKit"
  pod 'PsiphonClientCommonLibrary', :git => "https://github.com/Psiphon-Inc/psiphon-ios-client-common-library.git", :commit => 'f97b258'
  #pod "PsiphonClientCommonLibrary", :path => "../psiphon-ios-client-common-library"

  pod 'ReactiveObjC', :git => "https://github.com/Psiphon-Inc/ReactiveObjC.git", :commit => '8bbf9dd'
  pod 'mopub-ios-sdk', '~> 5.4'
  pod 'MoPub-AdMob-Adapters', '~> 7.37'
  pod 'Google-Mobile-Ads-SDK', '~> 7.37'
  pod 'PersonalizedAdConsent'  # Google Mobile Ads Consent SDK
  pod 'MBProgressHUD', '~> 1.1.0'
  pod 'CustomIOSAlertView', '~> 0.9.5'
  pod 'SVProgressHUD'
end

target 'PsiphonVPN' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  #use_frameworks!

  pod 'ReactiveObjC', :git => "https://github.com/Psiphon-Inc/ReactiveObjC.git", :commit => '8bbf9dd'

end
