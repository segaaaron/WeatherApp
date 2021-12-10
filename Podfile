# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'WeatherApp' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for WeatherApp
  pod 'FLAnimatedImage', '~> 1.0.12'
  pod 'IGListKit', '~> 4.0.0'
  pod 'IGListDiffKit', '~> 4.0.0'
  pod 'IQKeyboardManagerSwift', '~> 6.5.0'
  pod 'RxGesture'
  pod 'RxCocoa'
  pod 'RxDataSources'
  pod 'RxRelay'
  pod 'lottie-ios', '~> 3.2.2'
  pod 'YoutubePlayer-in-WKWebView', '~> 0.3.4'

  target 'WeatherAppTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'WeatherAppUITests' do
    # Pods for testing
    pod 'Quick'
    pod 'Nimble'
    # Services Mocking
    pod 'OHHTTPStubs/Swift', '~> 9.0.0'
    # RX
    pod 'RxNimble', subspecs: ['RxBlocking', 'RxTest']
  end

end
