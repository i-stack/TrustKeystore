platform :ios, '10.0'

target 'TrustKeystore' do
  use_frameworks!

  pod 'BigInt', inhibit_warnings: true
  pod 'CryptoSwift', '~> 0.10.0'
  pod 'TrezorCrypto', '~> 0.0.9', inhibit_warnings: true
  #pod 'TrustCore', :git=>'https://github.com/TrustWallet/trust-core', :branch=> 'master', inhibit_warnings: true
  pod 'TrustCore', :git => 'https://github.com/i-stack/TrustCore.git', :commit => 'e2bcca8f35ae243e4ecd567d5cbf9468a7f4ee1d'
  pod 'SwiftLint'

  target 'KeystoreBenchmark'
  target 'TrustKeystoreTests'
end
