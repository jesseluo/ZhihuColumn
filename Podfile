ENV['COCOAPODS_DISABLE_STATS'] = "true"

platform :ios, '8.0'
use_frameworks!
inhibit_all_warnings!

target 'ZhihuColumn' do
  pod 'ReactiveCocoa', '~> 4.0.1'
  pod 'SnapKit', '~> 0.19.1'
  pod 'Alamofire', '~> 3.2.1'
end

def pods_for_test
  pod 'Quick', '~> 0.9.1'
  pod 'Nimble', '~> 3.2.0'
end

target 'ZhihuColumnTests' do
  pods_for_test
end

target 'ZhihuColumnUITests' do
  pods_for_test
end
