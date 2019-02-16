# platform :ios, "12.0"
use_frameworks!

project 'CrossPlatformApp'

def shared_pods

    pod 'GDLog', :path => '/Users/gene/Development/xcode/gene/Swift/mypods/GDLog'

end

def testing_pods
    pod 'Quick', '~> 1.2.0'
    pod 'Nimble', '~> 7.0.2'
end

target 'IOSApp' do
    shared_pods
end

target 'CocoaApp' do
    shared_pods
end

target 'SharedCocoa' do
    shared_pods
end

target 'SharedIOS' do
    shared_pods
end

target 'SharedCocoaTests' do
    shared_pods
    testing_pods
end

