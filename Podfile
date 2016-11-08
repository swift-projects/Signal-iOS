platform :ios, '8.0'
source 'https://github.com/CocoaPods/Specs.git'

target 'Signal' do
    pod 'SocketRocket',               :git => 'https://github.com/facebook/SocketRocket.git'
    pod 'SignalServiceKit',           git: 'https://github.com/WhisperSystems/SignalServiceKit.git'
    #pod 'SignalServiceKit',           path: '../SignalServiceKit'
    pod 'OpenSSL'
    pod 'PastelogKit',                '~> 1.3'
    pod 'FFCircularProgressView',     '~> 0.5'
    pod 'SCWaveformView',             '~> 1.0'
    pod 'ZXingObjC'
    pod 'DJWActionSheet'
    #pod 'JSQMessagesViewController'
    pod 'JSQMessagesViewController', git: 'https://github.com/WhisperSystems/JSQMessagesViewController.git', branch: 'fix-intermittent-crash-on-delete'
    target 'SignalTests' do
        inherit! :search_paths
    end
end