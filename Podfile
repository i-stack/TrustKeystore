platform :ios, '10.0'

target 'TrustKeystore' do
  use_frameworks!

  pod 'BigInt', inhibit_warnings: true
  pod 'TrezorCrypto', inhibit_warnings: true
#  pod 'TrustCore', :git=>'https://github.com/TrustWallet/trust-core', :branch=> 'master', inhibit_warnings: true
  pod 'TrustCore', :git => 'https://github.com/i-stack/TrustCore', :branch => 'TrustCore_0.0.7', inhibit_warnings: true

  pod 'SwiftLint'

  target 'KeystoreBenchmark'
  target 'TrustKeystoreTests'
end
