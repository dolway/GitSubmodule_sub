##推荐使用清华大学镜像源
#source 'https://mirrors.tuna.tsinghua.edu.cn/git/CocoaPods/Specs.git'
##忽略.cocoapods中多个specs源引起的警告问题
install! 'cocoapods', :warn_for_unused_master_specs_repo => false

platform :ios, '9.0'

#post_install do |installer|
#  installer.pods_project.build_configurations.each do |config|
#    config.build_settings["EXCLUDED_ARCHS[sdk=iphonesimulator*]"] = "arm64"
#  end
#end

abstract_target 'allTarget' do

#  pod 'ReactiveCocoa', '~> 10.1' // 新版都到10.1了
  pod 'ReactiveCocoa', '~> 2.5'
  pod 'AFNetworking', '~> 3.0.4'
  pod 'FMDB', '~> 2.6'
  pod 'MJExtension', '~> 3.0.10'
  pod 'Masonry', '~> 0.6.4'
  pod 'SVProgressHUD', '~> 2.2.5'
  pod 'IQKeyboardManager', '~> 4.0.0'
  pod 'JWT', '~> 3.0.0-beta.9'
  pod 'Zhugeio'
  pod 'JLLogEncoding', '~> 0.0.3'

  target 'GitSubmodule_Sub' do

    pod 'PLShortVideoKit'
  #  pod 'PLShortVideoKit', :podspec => 'https://raw.githubusercontent.com/pili-engineering/PLShortVideoKit/master/PLShortVideoKit-Smart.podspec'

    pod 'PLPlayerKit'
  #  pod "PLPlayerKit", :podspec => 'https://raw.githubusercontent.com/pili-engineering/PLPlayerKit/master/PLPlayerKit-Universal.podspec'
  end


end


