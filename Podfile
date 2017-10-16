platform :ios, '9.0'
swift_version = '3.2'
use_frameworks!

target 'StaticDI' do
  pod 'RxSwift', :git => 'https://github.com/ReactiveX/RxSwift.git', :tag => '4.0.0-rc.0'
  pod 'Sourcery', :git => 'https://github.com/krzysztofzablocki/Sourcery.git', :tag => '0.9.0'
  pod 'SwiftLint'

  target 'Presentation' do
    pod 'RxCocoa', :git => 'https://github.com/ReactiveX/RxSwift.git', :tag => '4.0.0-rc.0'

    target 'PresentationTests' do
      inherit! :search_paths
      pod 'Quick', :git => 'https://github.com/Quick/Quick.git', :tag => 'v1.2.0'
      pod 'Nimble', :git => 'https://github.com/Quick/Nimble.git', :tag => 'v7.0.2'
      pod 'RxTest', :git => 'https://github.com/ReactiveX/RxSwift.git', :tag => '4.0.0-rc.0'
    end
  end

  target 'Domain' do
    target 'DomainTests' do
      inherit! :search_paths
      pod 'Quick', :git => 'https://github.com/Quick/Quick.git', :tag => 'v1.2.0'
      pod 'Nimble', :git => 'https://github.com/Quick/Nimble.git', :tag => 'v7.0.2'
      pod 'RxBlocking', :git => 'https://github.com/ReactiveX/RxSwift.git', :tag => '4.0.0-rc.0'
    end
  end

  target 'Infrastructure' do
    pod 'RealmSwift'

    target 'InfrastructureTests' do
      inherit! :search_paths
      pod 'Quick', :git => 'https://github.com/Quick/Quick.git', :tag => 'v1.2.0'
      pod 'Nimble', :git => 'https://github.com/Quick/Nimble.git', :tag => 'v7.0.2'
      pod 'RxBlocking', :git => 'https://github.com/ReactiveX/RxSwift.git', :tag => '4.0.0-rc.0'
    end
  end

  target 'Utility' do
    pod 'SwiftyBeaver'
  end
end
