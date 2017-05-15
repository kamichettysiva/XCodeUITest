# XCodeUITest
Demo Project XCode UI Testing.

Steps to use this demo project.

Colone the project
Open the project directory terminal
Run the below command from terminal.
xcodebuild -workspace TestWS.xcworkspace -scheme SimpleCalcUITests -sdk iphonesimulator -destination 'platform=iOS Simulator,name=iPhone 7 Plus' test

The Terminal output will be something like below.

Build settings from command line: SDKROOT = iphonesimulator10.3

2017-05-15 13:26:38.621 xcodebuild[3463:75193] IDETestOperationsObserverDebug: Writing diagnostic log for test session to: /Users/sivakumar/Library/Developer/Xcode/DerivedData/TestWS-anymlhfqpqtuwscjnpcbiikaqoqp/Logs/Test/C80DDC13-A2A0-4661-901C-7408096D7F0F/Session-SimpleCalcTests-2017-05-15_132638-kLqFXU.log 2017-05-15 13:26:38.621 xcodebuild[3463:75189] [MT] IDETestOperationsObserverDebug: (666103EA-CC97-40BA-B04C-9E5B96F90E71) Beginning test session SimpleCalcTests-666103EA-CC97-40BA-B04C-9E5B96F90E71 at 2017-05-15 13:26:38.621 with Xcode 8E1000a on target <DVTiPhoneSimulator: 0x7f893f043730> { SimDevice: SimDevice : iPhone 7 Plus (AEB4A701-905D-48B2-9B67-0D528DE339C0) : state={ Booted } deviceType={ SimDeviceType : com.apple.CoreSimulator.SimDeviceType.iPhone-7-Plus } runtime={ SimRuntime : 10.3 (14E269) - com.apple.CoreSimulator.SimRuntime.iOS-10-3 }

Test Case '-[SimpleCalcUITests.SimpleCalcUITests test2]' passed (16.430 seconds). Test Suite 'SimpleCalcUITests' passed at 2017-05-15 13:27:23.049. Executed 2 tests, with 0 failures (0 unexpected) in 32.552 (32.553) seconds Test Suite 'SimpleCalcUITests.xctest' passed at 2017-05-15 13:27:23.050. Executed 2 tests, with 0 failures (0 unexpected) in 32.552 (32.554) seconds Test Suite 'All tests' passed at 2017-05-15 13:27:23.050. Executed 2 tests, with 0 failures (0 unexpected) in 32.552 (32.555) seconds ** TEST SUCCEEDED **
