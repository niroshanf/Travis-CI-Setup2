# Uncomment the next line to define a global platform for your project
platform :ios, '11.0'

def shared_pods
  #pod "aaadaptiveCollectionView", :git => 'https://github.com/menews/aaadaptiveCollectionView.git'
  #pod 'ANFAdaptiveCollectionView'
  pod "aaadaptiveCollectionView", :git => 'git@github.com:menews/aaadaptiveCollectionView.git'
end

target 'Arabic' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Arabic
  shared_pods

  target 'ArabicTests' do
    inherit! :search_paths
    # Pods for testing
    shared_pods

  end

  target 'ArabicUITests' do
    # Pods for testing
  end

end

target 'English' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for English
  shared_pods

  target 'EnglishTests' do
    inherit! :search_paths
    # Pods for testing
    shared_pods
  end

  target 'EnglishUITests' do
    # Pods for testing
  end

end

target 'Travis-CI-Setup2' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Travis-CI-Setup2

  target 'Travis-CI-Setup2Tests' do
    # Pods for testing
  end

end
