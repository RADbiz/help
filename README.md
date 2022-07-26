# help :"70906002","platform":2,"bundleID":"com.agilebits.onepassword-ios","share_with_app_devs":0,"is_first_party":0,"bug_type":"309","os_version":"iPhone OS 15.6 (19G71)","incident_id":"CDBEFDA1-0C91-4B35-8D18-5F0A019EBE5F","name":"1Password"}
{
  "uptime" : 42000,
  "procLaunch" : "2022-07-22 21:23:09.2484 +1000",
  "procRole" : "Foreground",
  "version" : 2,
  "userID" : 501,
  "deployVersion" : 210,
  "modelCode" : "iPhone14,2",
  "procStartAbsTime" : 994496273338,
  "coalitionID" : 910,
  "osVersion" : {
    "isEmbedded" : true,
    "train" : "iPhone OS 15.6",
    "releaseType" : "User",
    "build" : "19G71"
  },
  "captureTime" : "2022-07-22 21:37:31.2683 +1000",
  "incident" : "CDBEFDA1-0C91-4B35-8D18-5F0A019EBE5F",
  "bug_type" : "309",
  "pid" : 4362,
  "procExitAbsTime" : 1015184501307,
  "cpuType" : "ARM-64",
  "procName" : "1Password",
  "procPath" : "\/private\/var\/containers\/Bundle\/Application\/50DF2D05-864B-4A01-A3B2-A2F804E63DFD\/1Password.app\/1Password",
  "bundleInfo" : {"CFBundleShortVersionString":"7.9.6","CFBundleVersion":"70906002","CFBundleIdentifier":"com.agilebits.onepassword-ios","DTAppStoreToolsBuild":"13F15"},
  "storeInfo" : {"storeCohortMetadata":"10|date=1658487600000&sf=143460&rapp=org.mozilla.ios.Firefox&pgtp=Software&pgid=568903335&ctxt=Today&lngid=27","itemID":"568903335","deviceIdentifierForVendor":"A820CA30-AC5A-4049-92D9-97AB214904B5","softwareVersionExternalIdentifier":"849205895","thirdParty":true,"applicationVariant":"1:iPhone14,2:15"},
  "parentProc" : "launchd",
  "parentPid" : 1,
  "coalitionName" : "com.agilebits.onepassword-ios",
  "crashReporterKey" : "ccc91f1e6e65df38e6bd8e1d368406d15d457b0d",
  "basebandVersion" : "1.70.01",
  "isCorpse" : 1,
  "exception" : {"codes":"0x0000000000000000, 0x0000000000000000","rawCodes":[0,0],"type":"EXC_CRASH","signal":"SIGABRT"},
  "asi" : {"libsystem_c.dylib":["abort() called"]},
  "lastExceptionBacktrace" : [{"imageOffset":627336,"symbol":"__exceptionPreprocess","symbolLocation":220,"imageIndex":4},{"imageOffset":91972,"symbol":"objc_exception_throw","symbolLocation":60,"imageIndex":5},{"imageOffset":983952,"symbol":"__CFDictionaryCreateGeneric","symbolLocation":0,"imageIndex":4},{"imageOffset":3465140,"symbol":"-[UITableView _contentOffsetForScrollingToRowAtIndexPath:atScrollPosition:usingPresentationValues:]","symbolLocation":472,"imageIndex":7},{"imageOffset":3352608,"symbol":"-[UITableView _scrollToRowAtIndexPath:atScrollPosition:animated:usingPresentationValues:]","symbolLocation":192,"imageIndex":7},{"imageOffset":3647960,"symbol":"-[UITableView scrollToRowAtIndexPath:atScrollPosition:animated:]","symbolLocation":144,"imageIndex":7},{"imageOffset":481160,"symbol":"__52-[OPItemEditorTableViewController keyboardWillShow:]_block_invoke","symbolLocation":328,"imageIndex":8},{"imageOffset":101560,"symbol":"-[OPCustomTableViewController keyboardWillShow:completion:]","symbolLocation":780,"imageIndex":8},{"imageOffset":480760,"symbol":"-[OPItemEditorTableViewController keyboardWillShow:]","symbolLocation":160,"imageIndex":8},{"imageOffset":174132,"symbol":"__CFNOTIFICATIONCENTER_IS_CALLING_OUT_TO_AN_OBSERVER__","symbolLocation":28,"imageIndex":4},{"imageOffset":815060,"symbol":"___CFXRegistrationPost_block_invoke","symbolLocation":52,"imageIndex":4},{"imageOffset":631248,"symbol":"_CFXRegistrationPost","symbolLocation":456,"imageIndex":4},{"imageOffset":264364,"symbol":"_CFXNotificationPost","symbolLocation":728,"imageIndex":4},{"imageOffset":112436,"symbol":"-[NSNotificationCenter postNotificationName:object:userInfo:]","symbolLocation":96,"imageIndex":9},{"imageOffset":4803816,"symbol":"__68-[UIInputWindowController postValidatedStartNotifications:withInfo:]_block_invoke","symbolLocation":1164,"imageIndex":7},{"imageOffset":4857020,"symbol":"-[UIInputWindowController postValidatedStartNotifications:withInfo:]","symbolLocation":196,"imageIndex":7},{"imageOffset":13891364,"symbol":"__77-[UIInputWindowController moveFromPlacement:toPlacement:starting:completion:]_block_invoke.1015","symbolLocation":688,"imageIndex":7},{"imageOffset":4601952,"symbol":"+[UIView(UIViewAnimationWithBlocksPrivate) _modifyAnimationsWithPreferredFrameRateRange:updateReason:animations:]","symbolLocation":176,"imageIndex":7},{"imageOffset":1593472,"symbol":"+[UIView _setupAnimationWithDuration:delay:view:options:factory:animations:start:animationStateGenerator:completion:]","symbolLocation":644,"imageIndex":7},{"imageOffset":5818300,"symbol":"-[UIInputViewAnimationStyle launchAnimation:afterStarted:completion:forHost:fromCurrentPosition:]","symbolLocation":252,"imageIndex":7},{"imageOffset":4863528,"symbol":"-[UIInputWindowController moveFromPlacement:toPlacement:starting:completion:]","symbolLocation":2240,"imageIndex":7},{"imageOffset":5009352,"symbol":"-[UIInputWindowController setInputViewSet:]","symbolLocation":1808,"imageIndex":7},{"imageOffset":4552592,"symbol":"-[UIInputWindowController performOperations:withAnimationStyle:]","symbolLocation":60,"imageIndex":7},{"imageOffset":4403696,"symbol":"-[UIKeyboardSceneDelegate setKeyWindowSceneInputViews:animationStyle:]","symbolLocation":2448,"imageIndex":7},{"imageOffset":5032500,"symbol":"-[UIKeyboardSceneDelegate setInputViews:animationStyle:]","symbolLocation":256,"imageIndex":7},{"imageOffset":2226992,"symbol":"-[UIKeyboardSceneDelegate setInputViews:animated:]","symbolLocation":100,"imageIndex":7},{"imageOffset":3012144,"symbol":"-[UIKeyboardSceneDelegate setInputViews:]","symbolLocation":80,"imageIndex":7},{"imageOffset":11137228,"symbol":"__71-[UIKeyboardSceneDelegate _reloadInputViewsForKeyWindowSceneResponder:]_block_invoke.713","symbolLocation":40,"imageIndex":7},{"imageOffset":3213736,"symbol":"-[UIKeyboardSceneDelegate _reloadInputViewsForKeyWindowSceneResponder:]","symbolLocation":3936,"imageIndex":7},{"imageOffset":1953172,"symbol":"-[UIKeyboardSceneDelegate _reloadInputViewsForResponder:]","symbolLocation":164,"imageIndex":7},{"imageOffset":2590168,"symbol":"-[UIResponder(UIResponderInputViewAdditions) reloadInputViews]","symbolLocation":132,"imageIndex":7},{"imageOffset":10450884,"symbol":"-[WKContentView(WKInteraction) _elementDidFocus:userIsInteracting:blurPreviousNode:activityStateChanges:userObject:]","symbolLocation":1880,"imageIndex":10},{"imageOffset":4981264,"symbol":"WebKit::WebPageProxy::elementDidFocus(WebKit::FocusedElementInformation const&, bool, bool, WTF::OptionSet<WebCore::ActivityState::Flag>, WebKit::UserData const&)","symbolLocation":180,"imageIndex":10},{"imageOffset":9737564,"symbol":"WebKit::WebPageProxy::didReceiveMessage(IPC::Connection&, IPC::Decoder&)","symbolLocation":87420,"imageIndex":10},{"imageOffset":3771920,"symbol":"IPC::MessageReceiverMap::dispatchMessage(IPC::Connection&, IPC::Decoder&)","symbolLocation":448,"imageIndex":10},{"imageOffset":6181228,"symbol":"WebKit::WebProcessProxy::didReceiveMessage(IPC::Connection&, IPC::Decoder&)","symbolLocation":40,"imageIndex":10},{"imageOffset":3662576,"symbol":"IPC::Connection::dispatchMessage(std::__1::unique_ptr<IPC::Decoder, std::__1::default_delete<IPC::Decoder> >)","symbolLocation":264,"imageIndex":10},{"imageOffset":3660552,"symbol":"IPC::Connection::dispatchIncomingMessages()","symbolLocation":468,"imageIndex":10},{"imageOffset":321520,"symbol":"WTF::RunLoop::performWork()","symbolLocation":200,"imageIndex":11},{"imageOffset":325004,"symbol":"WTF::RunLoop::performWork(void*)","symbolLocation":36,"imageIndex":11},{"imageOffset":766996,"symbol":"__CFRUNLOOP_IS_CALLING_OUT_TO_A_SOURCE0_PERFORM_FUNCTION__","symbolLocation":28,"imageIndex":4},{"imageOffset":836000,"symbol":"__CFRunLoopDoSource0","symbolLocation":208,"imageIndex":4},{"imageOffset":22164,"symbol":"__CFRunLoopDoSources0","symbolLocation":268,"imageIndex":4},{"imageOffset":45148,"symbol":"__CFRunLoopRun","symbolLocation":828,"imageIndex":4},{"imageOffset":125896,"symbol":"CFRunLoopRunSpecific","symbolLocation":600,"imageIndex":4},{"imageOffset":4980,"symbol":"GSEventRunModal","symbolLocation":164,"imageIndex":12},{"imageOffset":5327704,"symbol":"-[UIApplication _run]","symbolLocation":1100,"imageIndex":7},{"imageOffset":2711696,"symbol":"UIApplicationMain","symbolLocation":364,"imageIndex":7},{"imageOffset":133208,"imageIndex":13},{"imageOffset":105892,"symbol":"start","symbolLocation":520,"imageIndex":14}],
  "faultingThread" : 0,
  "threads" : [{"triggered":true,"id":403760,"threadState":{"x":[{"value":0},{"value":0},{"value":0},{"value":0},{"value":16},{"value":16},{"value":4969013888},{"value":252416},{"value":11223199070725022172},{"value":11223199066414507100},{"value":216172790139653793,"symbolLocation":216172782113783809,"symbol":"OBJC_CLASS_$_NSException"},{"value":288230384177581729,"symbolLocation":288230376151711745,"symbol":"OBJC_CLASS_$_NSException"},{"value":62},{"value":4430930384},{"value":4},{"value":8025914128,"symbolLocation":0,"symbol":"OBJC_CLASS_$__NSCallStackArray"},{"value":328},{"value":4348364160,"symbolLocation":0,"symbol":"_main_thread"},{"value":0},{"value":6},{"value":259},{"value":4348364384,"symbolLocation":224,"symbol":"_main_thread"},{"value":4432035840},{"value":8042774968,"symbolLocation":0,"symbol":"__kCFAllocatorSystemDefault"},{"value":50},{"value":7770557294,"objc-selector":"objectAtIndex:"},{"value":7776606968,"objc-selector":"unsignedIntegerValue"},{"value":6527886515,"symbolLocation":12210,"symbol":"_CFStringCreateByAddingPercentEncodingWithAllowedCharacters.hexchars"},{"value":7977572856,"symbolLocation":0,"symbol":"__last_exception_backtrace__"}],"flavor":"ARM_THREAD_STATE64","lr":{"value":8430302140},"cpsr":{"value":1073745920},"fp":{"value":6123901168},"sp":{"value":6123901136},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":7459916600,"matchesCrashFrame":1},"far":{"value":4351803399}},"queue":"com.apple.main-thread","frames":[{"imageOffset":31544,"symbol":"__pthread_kill","symbolLocation":8,"imageIndex":0},{"imageOffset":29628,"symbol":"pthread_kill","symbolLocation":268,"imageIndex":1},{"imageOffset":132388,"symbol":"abort","symbolLocation":168,"imageIndex":2},{"imageOffset":161984,"symbol":"uncaught_exception_handler.cold.1","symbolLocation":28,"imageIndex":3},{"imageOffset":157868,"symbol":"uncaught_exception_handler","symbolLocation":44,"imageIndex":3},{"imageOffset":1156464,"symbol":"__handleUncaughtException","symbolLocation":712,"imageIndex":4},{"imageOffset":117852,"symbol":"_objc_terminate()","symbolLocation":132,"imageIndex":5},{"imageOffset":112160,"symbol":"MSACCrashesUncaughtCXXTerminateHandler()","symbolLocation":712,"imageIndex":3},{"imageOffset":69400,"symbol":"std::__terminate(void (*)())","symbolLocation":20,"imageIndex":6},{"imageOffset":80924,"symbol":"__cxxabiv1::failed_throw(__cxxabiv1::__cxa_exception*)","symbolLocation":36,"imageIndex":6},{"imageOffset":80840,"symbol":"__cxa_throw","symbolLocation":140,"imageIndex":6},{"imageOffset":92332,"symbol":"objc_exception_throw","symbolLocation":420,"imageIndex":5},{"imageOffset":983952,"symbol":"+[NSException raise:format:]","symbolLocation":112,"imageIndex":4},{"imageOffset":3465140,"symbol":"-[UITableView _contentOffsetForScrollingToRowAtIndexPath:atScrollPosition:usingPresentationValues:]","symbolLocation":472,"imageIndex":7},{"imageOffset":3352608,"symbol":"-[UITableView _scrollToRowAtIndexPath:atScrollPosition:animated:usingPresentationValues:]","symbolLocation":192,"imageIndex":7},{"imageOffset":3647960,"symbol":"-[UITableView scrollToRowAtIndexPath:atScrollPosition:animated:]","symbolLocation":144,"imageIndex":7},{"imageOffset":481160,"symbol":"__52-[OPItemEditorTableViewController keyboardWillShow:]_block_invoke","symbolLocation":328,"imageIndex":8},{"imageOffset":101560,"symbol":"-[OPCustomTableViewController keyboardWillShow:completion:]","symbolLocation":780,"imageIndex":8},{"imageOffset":480760,"symbol":"-[OPItemEditorTableViewController keyboardWillShow:]","symbolLocation":160,"imageIndex":8},{"imageOffset":174132,"symbol":"__CFNOTIFICATIONCENTER_IS_CALLING_OUT_TO_AN_OBSERVER__","symbolLocation":28,"imageIndex":4},{"imageOffset":815060,"symbol":"___CFXRegistrationPost_block_invoke","symbolLocation":52,"imageIndex":4},{"imageOffset":631248,"symbol":"_CFXRegistrationPost","symbolLocation":456,"imageIndex":4},{"imageOffset":264364,"symbol":"_CFXNotificationPost","symbolLocation":728,"imageIndex":4},{"imageOffset":112436,"symbol":"-[NSNotificationCenter postNotificationName:object:userInfo:]","symbolLocation":96,"imageIndex":9},{"imageOffset":4803816,"symbol":"__68-[UIInputWindowController postValidatedStartNotifications:withInfo:]_block_invoke","symbolLocation":1164,"imageIndex":7},{"imageOffset":4857020,"symbol":"-[UIInputWindowController postValidatedStartNotifications:withInfo:]","symbolLocation":196,"imageIndex":7},{"imageOffset":13891364,"symbol":"__77-[UIInputWindowController moveFromPlacement:toPlacement:starting:completion:]_block_invoke.1015","symbolLocation":688,"imageIndex":7},{"imageOffset":4601952,"symbol":"+[UIView(UIViewAnimationWithBlocksPrivate) _modifyAnimationsWithPreferredFrameRateRange:updateReason:animations:]","symbolLocation":176,"imageIndex":7},{"imageOffset":1593472,"symbol":"+[UIView _setupAnimationWithDuration:delay:view:options:factory:animations:start:animationStateGenerator:completion:]","symbolLocation":644,"imageIndex":7},{"imageOffset":5818300,"symbol":"-[UIInputViewAnimationStyle launchAnimation:afterStarted:completion:forHost:fromCurrentPosition:]","symbolLocation":252,"imageIndex":7},{"imageOffset":4863528,"symbol":"-[UIInputWindowController moveFromPlacement:toPlacement:starting:completion:]","symbolLocation":2240,"imageIndex":7},{"imageOffset":5009352,"symbol":"-[UIInputWindowController setInputViewSet:]","symbolLocation":1808,"imageIndex":7},{"imageOffset":4552592,"symbol":"-[UIInputWindowController performOperations:withAnimationStyle:]","symbolLocation":60,"imageIndex":7},{"imageOffset":4403696,"symbol":"-[UIKeyboardSceneDelegate setKeyWindowSceneInputViews:animationStyle:]","symbolLocation":2448,"imageIndex":7},{"imageOffset":5032500,"symbol":"-[UIKeyboardSceneDelegate setInputViews:animationStyle:]","symbolLocation":256,"imageIndex":7},{"imageOffset":2226992,"symbol":"-[UIKeyboardSceneDelegate setInputViews:animated:]","symbolLocation":100,"imageIndex":7},{"imageOffset":3012144,"symbol":"-[UIKeyboardSceneDelegate setInputViews:]","symbolLocation":80,"imageIndex":7},{"imageOffset":11137228,"symbol":"__71-[UIKeyboardSceneDelegate _reloadInputViewsForKeyWindowSceneResponder:]_block_invoke.713","symbolLocation":40,"imageIndex":7},{"imageOffset":3213736,"symbol":"-[UIKeyboardSceneDelegate _reloadInputViewsForKeyWindowSceneResponder:]","symbolLocation":3936,"imageIndex":7},{"imageOffset":1953172,"symbol":"-[UIKeyboardSceneDelegate _reloadInputViewsForResponder:]","symbolLocation":164,"imageIndex":7},{"imageOffset":2590168,"symbol":"-[UIResponder(UIResponderInputViewAdditions) reloadInputViews]","symbolLocation":132,"imageIndex":7},{"imageOffset":10450884,"symbol":"-[WKContentView(WKInteraction) _elementDidFocus:userIsInteracting:blurPreviousNode:activityStateChanges:userObject:]","symbolLocation":1880,"imageIndex":10},{"imageOffset":4981264,"symbol":"WebKit::WebPageProxy::elementDidFocus(WebKit::FocusedElementInformation const&, bool, bool, WTF::OptionSet<WebCore::ActivityState::Flag>, WebKit::UserData const&)","symbolLocation":180,"imageIndex":10},{"imageOffset":9737564,"symbol":"WebKit::WebPageProxy::didReceiveMessage(IPC::Connection&, IPC::Decoder&)","symbolLocation":87420,"imageIndex":10},{"imageOffset":3771920,"symbol":"IPC::MessageReceiverMap::dispatchMessage(IPC::Connection&, IPC::Decoder&)","symbolLocation":448,"imageIndex":10},{"imageOffset":6181228,"symbol":"WebKit::WebProcessProxy::didReceiveMessage(IPC::Connection&, IPC::Decoder&)","symbolLocation":40,"imageIndex":10},{"imageOffset":3662576,"symbol":"IPC::Connection::dispatchMessage(std::__1::unique_ptr<IPC::Decoder, std::__1::default_delete<IPC::Decoder> >)","symbolLocation":264,"imageIndex":10},{"imageOffset":3660552,"symbol":"IPC::Connection::dispatchIncomingMessages()","symbolLocation":468,"imageIndex":10},{"imageOffset":321520,"symbol":"WTF::RunLoop::performWork()","symbolLocation":200,"imageIndex":11},{"imageOffset":325004,"symbol":"WTF::RunLoop::performWork(void*)","symbolLocation":36,"imageIndex":11},{"imageOffset":766996,"symbol":"__CFRUNLOOP_IS_CALLING_OUT_TO_A_SOURCE0_PERFORM_FUNCTION__","symbolLocation":28,"imageIndex":4},{"imageOffset":836000,"symbol":"__CFRunLoopDoSource0","symbolLocation":208,"imageIndex":4},{"imageOffset":22164,"symbol":"__CFRunLoopDoSources0","symbolLocation":268,"imageIndex":4},{"imageOffset":45148,"symbol":"__CFRunLoopRun","symbolLocation":828,"imageIndex":4},{"imageOffset":125896,"symbol":"CFRunLoopRunSpecific","symbolLocation":600,"imageIndex":4},{"imageOffset":4980,"symbol":"GSEventRunModal","symbolLocation":164,"imageIndex":12},{"imageOffset":5327704,"symbol":"-[UIApplication _run]","symbolLocation":1100,"imageIndex":7},{"imageOffset":2711696,"symbol":"UIApplicationMain","symbolLocation":364,"imageIndex":7},{"imageOffset":133208,"imageIndex":13},{"imageOffset":105892,"symbol":"start","symbolLocation":520,"imageIndex":14}]},{"id":403778,"name":"com.apple.uikit.eventfetch-thread","frames":[{"imageOffset":5280,"symbol":"mach_msg_trap","symbolLocation":8,"imageIndex":0},{"imageOffset":6884,"symbol":"mach_msg","symbolLocation":76,"imageIndex":0},{"imageOffset":27952,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":372,"imageIndex":4},{"imageOffset":45500,"symbol":"__CFRunLoopRun","symbolLocation":1180,"imageIndex":4},{"imageOffset":125896,"symbol":"CFRunLoopRunSpecific","symbolLocation":600,"imageIndex":4},{"imageOffset":103492,"symbol":"-[NSRunLoop(NSRunLoop) runMode:beforeDate:]","symbolLocation":236,"imageIndex":9},{"imageOffset":372236,"symbol":"-[NSRunLoop(NSRunLoop) runUntilDate:]","symbolLocation":92,"imageIndex":9},{"imageOffset":4779204,"symbol":"-[UIEventFetcher threadMain]","symbolLocation":524,"imageIndex":7},{"imageOffset":431132,"symbol":"__NSThread__start__","symbolLocation":808,"imageIndex":9},{"imageOffset":6572,"symbol":"_pthread_start","symbolLocation":148,"imageIndex":1},{"imageOffset":3688,"symbol":"thread_start","symbolLocation":8,"imageIndex":1}]},{"id":403838,"frames":[{"imageOffset":5280,"symbol":"mach_msg_trap","symbolLocation":8,"imageIndex":0},{"imageOffset":6884,"symbol":"mach_msg","symbolLocation":76,"imageIndex":0},{"imageOffset":210060,"symbol":"exception_server_thread","symbolLocation":188,"imageIndex":3},{"imageOffset":6572,"symbol":"_pthread_start","symbolLocation":148,"imageIndex":1},{"imageOffset":3688,"symbol":"thread_start","symbolLocation":8,"imageIndex":1}]},{"id":403864,"name":"com.apple.NSURLConnectionLoader","frames":[{"imageOffset":5280,"symbol":"mach_msg_trap","symbolLocation":8,"imageIndex":0},{"imageOffset":6884,"symbol":"mach_msg","symbolLocation":76,"imageIndex":0},{"imageOffset":27952,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":372,"imageIndex":4},{"imageOffset":45500,"symbol":"__CFRunLoopRun","symbolLocation":1180,"imageIndex":4},{"imageOffset":125896,"symbol":"CFRunLoopRunSpecific","symbolLocation":600,"imageIndex":4},{"imageOffset":2589148,"imageIndex":15},{"imageOffset":431132,"symbol":"__NSThread__start__","symbolLocation":808,"imageIndex":9},{"imageOffset":6572,"symbol":"_pthread_start","symbolLocation":148,"imageIndex":1},{"imageOffset":3688,"symbol":"thread_start","symbolLocation":8,"imageIndex":1}]},{"id":406996,"name":"com.apple.CFSocket.private","frames":[{"imageOffset":8548,"symbol":"__select","symbolLocation":8,"imageIndex":0},{"imageOffset":699240,"symbol":"__CFSocketManager","symbolLocation":644,"imageIndex":4},{"imageOffset":6572,"symbol":"_pthread_start","symbolLocation":148,"imageIndex":1},{"imageOffset":3688,"symbol":"thread_start","symbolLocation":8,"imageIndex":1}]},{"id":409809,"name":"AVAudioSession Notify Thread","frames":[{"imageOffset":5280,"symbol":"mach_msg_trap","symbolLocation":8,"imageIndex":0},{"imageOffset":6884,"symbol":"mach_msg","symbolLocation":76,"imageIndex":0},{"imageOffset":27952,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":372,"imageIndex":4},{"imageOffset":45500,"symbol":"__CFRunLoopRun","symbolLocation":1180,"imageIndex":4},{"imageOffset":125896,"symbol":"CFRunLoopRunSpecific","symbolLocation":600,"imageIndex":4},{"imageOffset":28420,"symbol":"CADeprecated::GenericRunLoopThread::Entry(void*)","symbolLocation":164,"imageIndex":16},{"imageOffset":67824,"symbol":"CADeprecated::CAPThread::Entry(CADeprecated::CAPThread*)","symbolLocation":92,"imageIndex":16},{"imageOffset":6572,"symbol":"_pthread_start","symbolLocation":148,"imageIndex":1},{"imageOffset":3688,"symbol":"thread_start","symbolLocation":8,"imageIndex":1}]},{"id":410020,"name":"H11ANEServicesThread","frames":[{"imageOffset":5280,"symbol":"mach_msg_trap","symbolLocation":8,"imageIndex":0},{"imageOffset":6884,"symbol":"mach_msg","symbolLocation":76,"imageIndex":0},{"imageOffset":27952,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":372,"imageIndex":4},{"imageOffset":45500,"symbol":"__CFRunLoopRun","symbolLocation":1180,"imageIndex":4},{"imageOffset":125896,"symbol":"CFRunLoopRunSpecific","symbolLocation":600,"imageIndex":4},{"imageOffset":654760,"symbol":"CFRunLoopRun","symbolLocation":64,"imageIndex":4},{"imageOffset":65300,"symbol":"H11ANE::H11ANEServicesThreadStart(H11ANE::H11ANEServicesThreadParams*)","symbolLocation":132,"imageIndex":17},{"imageOffset":6572,"symbol":"_pthread_start","symbolLocation":148,"imageIndex":1},{"imageOffset":3688,"symbol":"thread_start","symbolLocation":8,"imageIndex":1}]},{"id":412099,"frames":[{"imageOffset":3668,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":1}]},{"id":412257,"queue":"com.agilebits.AGLogger","frames":[{"imageOffset":20228,"symbol":"dyld3::MachOLoaded::findClosestSymbol(unsigned long long, char const**, unsigned long long*) const","symbolLocation":308,"imageIndex":14},{"imageOffset":20192,"symbol":"dyld3::MachOLoaded::findClosestSymbol(unsigned long long, char const**, unsigned long long*) const","symbolLocation":272,"imageIndex":14},{"imageOffset":28660,"symbol":"dyld4::APIs::dladdr(void const*, dl_info*)","symbolLocation":212,"imageIndex":14},{"imageOffset":163432,"symbol":"backtrace_symbols","symbolLocation":112,"imageIndex":2},{"imageOffset":791340,"symbol":"-[_NSCallStackArray objectAtIndex:]","symbolLocation":120,"imageIndex":9},{"imageOffset":1063008,"symbol":"-[NSArray getObjects:range:]","symbolLocation":140,"imageIndex":4},{"imageOffset":339596,"symbol":"-[NSArray countByEnumeratingWithState:objects:count:]","symbolLocation":184,"imageIndex":4},{"imageOffset":97364,"symbol":"__107-[AGLogger log:subsystemEnabled:object:objectDescription:method:methodName:file:line:assertionFormat:args:]_block_invoke","symbolLocation":208,"imageIndex":18},{"imageOffset":7788,"symbol":"_dispatch_call_block_and_release","symbolLocation":32,"imageIndex":19},{"imageOffset":14896,"symbol":"_dispatch_client_callout","symbolLocation":20,"imageIndex":19},{"imageOffset":45348,"symbol":"_dispatch_lane_serial_drain","symbolLocation":668,"imageIndex":19},{"imageOffset":48256,"symbol":"_dispatch_lane_invoke","symbolLocation":392,"imageIndex":19},{"imageOffset":91392,"symbol":"_dispatch_workloop_worker_thread","symbolLocation":648,"imageIndex":19},{"imageOffset":4284,"symbol":"_pthread_wqthread","symbolLocation":288,"imageIndex":1},{"imageOffset":3676,"symbol":"start_wqthread","symbolLocation":8,"imageIndex":1}]},{"id":412261,"frames":[{"imageOffset":3668,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":1}]},{"id":412342,"frames":[{"imageOffset":3668,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":1}]},{"id":412347,"name":"JavaScriptCore libpas scavenger","frames":[{"imageOffset":7972,"symbol":"__psynch_cvwait","symbolLocation":8,"imageIndex":0},{"imageOffset":33432,"symbol":"_pthread_cond_wait","symbolLocation":1236,"imageIndex":1},{"imageOffset":960104,"symbol":"scavenger_thread_main","symbolLocation":1232,"imageIndex":11},{"imageOffset":6572,"symbol":"_pthread_start","symbolLocation":148,"imageIndex":1},{"imageOffset":3688,"symbol":"thread_start","symbolLocation":8,"imageIndex":1}]}],
  "usedImages" : [
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7459885056,
    "size" : 221184,
    "uuid" : "9ab02ad0-348c-30cb-99f4-0979c2d47515",
    "path" : "\/usr\/lib\/system\/libsystem_kernel.dylib",
    "name" : "libsystem_kernel.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 8430272512,
    "size" : 49152,
    "uuid" : "a8989ffb-1414-39dc-a1a8-1534f21923fe",
    "path" : "\/usr\/lib\/system\/libsystem_pthread.dylib",
    "name" : "libsystem_pthread.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6710145024,
    "size" : 524288,
    "uuid" : "86a1a24a-ce35-3769-ba69-60f28353281e",
    "path" : "\/usr\/lib\/system\/libsystem_c.dylib",
    "name" : "libsystem_c.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 4351426560,
    "size" : 311296,
    "uuid" : "c37495c5-1964-382c-833e-de1eb9ec9be4",
    "path" : "\/private\/var\/containers\/Bundle\/Application\/50DF2D05-864B-4A01-A3B2-A2F804E63DFD\/1Password.app\/Frameworks\/AppCenterCrashes.framework\/AppCenterCrashes",
    "name" : "AppCenterCrashes"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6523977728,
    "size" : 4546560,
    "uuid" : "6b22dd81-3585-3be6-bc77-ba19810ec0f2",
    "path" : "\/System\/Library\/Frameworks\/CoreFoundation.framework\/CoreFoundation",
    "name" : "CoreFoundation"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6940991488,
    "size" : 249856,
    "uuid" : "f6368be9-109b-3405-b282-624040529afd",
    "path" : "\/usr\/lib\/libobjc.A.dylib",
    "name" : "libobjc.A.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6942105600,
    "size" : 98304,
    "uuid" : "d00067b2-0a7a-3cb9-b4d4-07b160da261b",
    "path" : "\/usr\/lib\/libc++abi.dylib",
    "name" : "libc++abi.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6562242560,
    "size" : 25812992,
    "uuid" : "137a95aa-da6d-332c-bc01-e13bb9b6e317",
    "path" : "\/System\/Library\/PrivateFrameworks\/UIKitCore.framework\/UIKitCore",
    "name" : "UIKitCore"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 4376887296,
    "size" : 1261568,
    "uuid" : "86c8cfe0-7f08-3185-8b5a-dc446b8bc6e9",
    "path" : "\/private\/var\/containers\/Bundle\/Application\/50DF2D05-864B-4A01-A3B2-A2F804E63DFD\/1Password.app\/Frameworks\/OnePasswordUI.framework\/OnePasswordUI",
    "name" : "OnePasswordUI"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6549110784,
    "size" : 3190784,
    "uuid" : "ee1abaf2-3d71-37fb-9067-15aa79528619",
    "path" : "\/System\/Library\/Frameworks\/Foundation.framework\/Foundation",
    "name" : "Foundation"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6772428800,
    "size" : 11751424,
    "uuid" : "611f4f51-9b22-393c-9ece-9cb4258c3452",
    "path" : "\/System\/Library\/Frameworks\/WebKit.framework\/WebKit",
    "name" : "WebKit"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6711029760,
    "size" : 21512192,
    "uuid" : "2199c812-0cf5-36d7-9d9f-8ae2c4422d13",
    "path" : "\/System\/Library\/Frameworks\/JavaScriptCore.framework\/JavaScriptCore",
    "name" : "JavaScriptCore"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6995345408,
    "size" : 36864,
    "uuid" : "a094e7b5-1d40-37c5-9027-56d86988ec4b",
    "path" : "\/System\/Library\/PrivateFrameworks\/GraphicsServices.framework\/GraphicsServices",
    "name" : "GraphicsServices"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 4342956032,
    "size" : 2359296,
    "uuid" : "e1cf2a26-cfb9-3065-8bf0-2e8c8b84af04",
    "path" : "\/private\/var\/containers\/Bundle\/Application\/50DF2D05-864B-4A01-A3B2-A2F804E63DFD\/1Password.app\/1Password",
    "name" : "1Password"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 4347920384,
    "size" : 360448,
    "uuid" : "66e1fb26-68f8-379b-a052-eb8b8291b5e1",
    "path" : "\/usr\/lib\/dyld",
    "name" : "dyld"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6532509696,
    "size" : 4988928,
    "uuid" : "106410ff-dd4f-3527-ad53-1980fe8b0ddd",
    "path" : "\/System\/Library\/Frameworks\/CFNetwork.framework\/CFNetwork",
    "name" : "CFNetwork"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6681448448,
    "size" : 176128,
    "uuid" : "98e46768-74ff-374c-9b70-303bffce2d33",
    "path" : "\/System\/Library\/PrivateFrameworks\/AudioSession.framework\/AudioSession",
    "name" : "AudioSession"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7609532416,
    "size" : 122880,
    "uuid" : "6d781ab0-84cf-37c8-815f-c42bd22fb19b",
    "path" : "\/System\/Library\/PrivateFrameworks\/ANEServices.framework\/ANEServices",
    "name" : "ANEServices"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 4350951424,
    "size" : 262144,
    "uuid" : "9f6a4156-dc83-3398-b586-ab46a2d94561",
    "path" : "\/private\/var\/containers\/Bundle\/Application\/50DF2D05-864B-4A01-A3B2-A2F804E63DFD\/1Password.app\/Frameworks\/AgileLibrary.framework\/AgileLibrary",
    "name" : "AgileLibrary"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6520819712,
    "size" : 286720,
    "uuid" : "e3ea4f63-5d11-342a-af19-9f58dbc8e259",
    "path" : "\/usr\/lib\/system\/libdispatch.dylib",
    "name" : "libdispatch.dylib"
  }
],
  "sharedCache" : {
  "base" : 6520487936,
  "size" : 2571206656,
  "uuid" : "ffe245be-9b2c-3ed6-9bb5-c8c0a17f67c1"
},
  "vmSummary" : "ReadOnly portion of Libraries: Total=843.3M resident=0K(0%) swapped_out_or_unallocated=843.3M(100%)\nWritable regions: Total=830.9M written=0K(0%) resident=0K(0%) swapped_out=0K(0%) unallocated=830.9M(100%)\n\n                                VIRTUAL   REGION \nREGION TYPE                        SIZE    COUNT (non-coalesced) \n===========                     =======  ======= \nAccelerate framework               384K        3 \nActivity Tracing                   256K        1 \nCG image                          2128K       51 \nCG raster data                    3968K       26 \nColorSync                          448K       25 \nCoreAnimation                     13.8M      300 \nCoreUI image data                 1456K        7 \nFoundation                          16K        1 \nKernel Alloc Once                   32K        1 \nMALLOC                           612.0M      210 \nMALLOC guard page                  192K       12 \nSQLite page cache                  640K       10 \nSTACK GUARD                        192K       12 \nStack                             6992K       12 \nVM_ALLOCATE                        320K        6 \nWebKit Malloc                    192.0M        5 \n__AUTH                            4291K      502 \n__AUTH_CONST                      24.0M      660 \n__CTF                               756        1 \n__DATA                            23.9M      669 \n__DATA_CONST                      25.3M      667 \n__DATA_DIRTY                      2255K      556 \n__FONT_DATA                          4K        1 \n__LINKEDIT                       201.1M       16 \n__OBJC_CONST                      6176K      467 \n__OBJC_RO                         92.2M        1 \n__OBJC_RW                         3536K        1 \n__TEXT                           642.2M      690 \n__UNICODE                          592K        1 \ndyld private memory               1952K       26 \nlibnetwork                        1664K       24 \nmapped file                      351.1M      347 \nshared memory                       48K        3 \n===========                     =======  ======= \nTOTAL                              2.2G     5314 \n",
  "legacyInfo" : {
  "threadTriggered" : {
    "queue" : "com.apple.main-thread"
  }
},
  "trialInfo" : {
  "rollouts" : [
    {
      "rolloutId" : "61af99aeda72d16a4beb7756",
      "factorPackIds" : {
        "SIRI_DIALOG_ASSETS" : "62b9afba7e9ada388efffaa0"
      },
      "deploymentId" : 240000262
    },
    {
      "rolloutId" : "60186475825c62000ccf5450",
      "factorPackIds" : {
        "SIRI_VALUE_INFERENCE_CONTACT_RESOLUTION" : "62bdc4218fe09c1632d841e9"
      },
      "deploymentId" : 240000023
    }
  ],
  "experiments" : [

  ]
