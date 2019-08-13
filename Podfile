source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '9.0'
inhibit_all_warnings!

workspace 'BraintreeDropIn.xcworkspace'

target 'DropInDemo' do
  pod 'AFNetworking'
  pod 'CardIO'
  pod 'PureLayout'
  pod 'InAppSettingsKit'

  pod "BraintreeDropIn", :path => "./"

  pod 'Braintree/Apple-Pay'
  pod 'Braintree/PayPal'
  pod 'Braintree/Venmo'
  pod 'Braintree/PaymentFlow', :git => 'https://github.com/sepych/braintree-ios.git', :commit => '76a4737f17778e0172b649c9418190c622f0144b'

end

abstract_target 'Tests' do
  pod 'Specta'
  pod 'Expecta'
  pod 'OCMock'
  pod 'OHHTTPStubs'

  target 'UnitTests'
end

