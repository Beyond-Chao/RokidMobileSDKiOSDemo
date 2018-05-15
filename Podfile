
platform :ios, '8.0'
use_frameworks!
inhibit_all_warnings!

workspace 'RokidSDKDemo.xcworkspace'

source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/aliyun/aliyun-specs.git'

target 'RokidSDKDemoSwift' do
  project 'RokidSDKDemoSwift/RokidSDKDemoSwift.xcodeproj'

  pod 'RokidSDK', '~> 0.0.1'
  pod 'SnapKit', '3.2.0'
  pod 'MJRefresh'
  pod 'MBProgressHUD', '~> 1.1.0'

end

target 'RokidSDKDemoObjc' do
  project 'RokidSDKDemoObjc/RokidSDKDemoObjc.xcodeproj'

pod 'RokidSDK', '~> 0.0.1'
  pod 'SnapKit', '3.2.0'
  pod 'MJRefresh'
  pod 'MBProgressHUD', '~> 1.1.0'
end


target 'DontUse' do
  project 'RokidSDKDemoObjc/RokidSDKDemoObjc.xcodeproj'
  pod 'SnapKit', '3.2.0'
  pod 'MJRefresh'
  pod 'MBProgressHUD', '~> 1.1.0'
end
