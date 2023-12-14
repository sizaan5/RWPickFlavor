platform :ios, '12.0'

target 'RWPickFlavor' do
    pod 'Alamofire', '~> 4.7'
    pod 'MBProgressHUD', '~> 1.1.0', :modular_headers => true
    
    post_install do |installer|
        installer.pods_project.targets.each do |target|
          target.build_configurations.each do |config|
            config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '12.0'
          end
        end
      end
end

