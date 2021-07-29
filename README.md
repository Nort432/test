{"app_name":"NewVisionIT.iOS","timestamp":"2021-07-28 09:21:50.00 -0700","app_version":"1.0.7","slice_uuid":"def53f5f-ee1b-320a-ae15-96b6650c5bec","adam_id":1575800899,"build_version":"1.3","platform":2,"bundleID":"com.VisionIT","share_with_app_devs":0,"is_first_party":0,"bug_type":"109","os_version":"iPhone OS 14.6 (18F72)","incident_id":"B698F053-75AA-4C02-A6AB-8FF207CB2871","name":"NewVisionIT.iOS"}
Incident Identifier: B698F053-75AA-4C02-A6AB-8FF207CB2871
CrashReporter Key:   6ba0043583f66ac4d016a1961c79daa701465c10
Hardware Model:      xxx
Process:             NewVisionIT.iOS [5074]
Path:                /private/var/containers/Bundle/Application/02239B46-30E2-4BD0-9935-76DBF92541F1/NewVisionIT.iOS.app/NewVisionIT.iOS
Identifier:          com.VisionIT
Version:             1.3 (1.0.7)
AppStoreTools:       12E506
Code Type:           ARM-64 (Native)
Role:                Foreground
Parent Process:      launchd [1]
Coalition:           com.VisionIT [1683]


Date/Time:           2021-07-28 09:21:50.1734 -0700
Launch Time:         2021-07-28 09:21:11.6125 -0700
OS Version:          iPhone OS 14.6 (18F72)
Release Type:        User
Baseband Version:    n/a
Report Version:      104

Exception Type:  EXC_CRASH (SIGABRT)
Exception Codes: 0x0000000000000000, 0x0000000000000000
Exception Note:  EXC_CORPSE_NOTIFY
Triggered by Thread:  0

Application Specific Information:
abort() called

Thread 0 name:  tid_103  Dispatch queue: com.apple.main-thread
Thread 0 Crashed:
0   libsystem_kernel.dylib        	0x00000001c3647334 0x1c361e000 + 168756
1   libsystem_pthread.dylib       	0x00000001e0b11a9c 0x1e0b0f000 + 10908
2   libsystem_c.dylib             	0x000000019eed9c10 0x19ee62000 + 490512
3   libsystem_c.dylib             	0x000000019eed9b9c 0x19ee62000 + 490396
4   NewVisionIT.iOS               	0x0000000106cba16c 0x104f7c000 + 30663020
5   NewVisionIT.iOS               	0x0000000106bd237c 0x104f7c000 + 29713276
6   NewVisionIT.iOS               	0x0000000106b73e74 0x104f7c000 + 29326964
7   NewVisionIT.iOS               	0x0000000106b72848 0x104f7c000 + 29321288
8   NewVisionIT.iOS               	0x0000000106b69b48 0x104f7c000 + 29285192
9   NewVisionIT.iOS               	0x000000010539616c 0x104f7c000 + 4301164
10  NewVisionIT.iOS               	0x000000010512a1cc 0x104f7c000 + 1761740
11  NewVisionIT.iOS               	0x00000001051300d4 0x104f7c000 + 1786068
12  NewVisionIT.iOS               	0x0000000105fa08dc 0x104f7c000 + 16926940
13  NewVisionIT.iOS               	0x0000000105354b40 0x104f7c000 + 4033344
14  NewVisionIT.iOS               	0x0000000106b84208 0x104f7c000 + 29393416
15  NewVisionIT.iOS               	0x0000000106c1b6f4 0x104f7c000 + 30013172
16  NewVisionIT.iOS               	0x0000000106c1ebe4 0x104f7c000 + 30026724
17  NewVisionIT.iOS               	0x0000000104f82c4c 0x104f7c000 + 27724
18  NewVisionIT.iOS               	0x0000000104f84cb0 0x104f7c000 + 36016
19  Foundation                    	0x0000000196efd488 0x196d84000 + 1545352
20  CoreFoundation                	0x0000000195aa59e8 0x195a02000 + 670184
21  CoreFoundation                	0x0000000195aa58e4 0x195a02000 + 669924
22  CoreFoundation                	0x0000000195aa4be8 0x195a02000 + 666600
23  CoreFoundation                	0x0000000195a9ebc8 0x195a02000 + 641992
24  CoreFoundation                	0x0000000195a9e360 0x195a02000 + 639840
25  GraphicsServices              	0x00000001ad0dc734 0x1ad0d9000 + 14132
26  UIKitCore                     	0x0000000198519584 0x19794f000 + 12363140
27  UIKitCore                     	0x000000019851edf4 0x19794f000 + 12385780
28  NewVisionIT.iOS               	0x0000000106000ad8 0x104f7c000 + 17320664
29  NewVisionIT.iOS               	0x0000000105f51f20 0x104f7c000 + 16604960
30  NewVisionIT.iOS               	0x0000000105f51ea4 0x104f7c000 + 16604836
31  NewVisionIT.iOS               	0x0000000104fb7234 0x104f7c000 + 242228
32  NewVisionIT.iOS               	0x0000000105354b40 0x104f7c000 + 4033344
33  NewVisionIT.iOS               	0x0000000106b84208 0x104f7c000 + 29393416
34  NewVisionIT.iOS               	0x0000000106c1b6f4 0x104f7c000 + 30013172
35  NewVisionIT.iOS               	0x0000000106c208f4 0x104f7c000 + 30034164
36  NewVisionIT.iOS               	0x0000000106b696b4 0x104f7c000 + 29284020
37  NewVisionIT.iOS               	0x0000000106cc14ac 0x104f7c000 + 30692524
38  NewVisionIT.iOS               	0x0000000104fb5ae8 0x104f7c000 + 236264
39  libdyld.dylib                 	0x000000019575acf8 0x195759000 + 7416

Thread 1 name:  SGen worker
Thread 1:
0   libsystem_kernel.dylib        	0x00000001c36470cc 0x1c361e000 + 168140
1   libsystem_pthread.dylib       	0x00000001e0b14434 0x1e0b0f000 + 21556
2   NewVisionIT.iOS               	0x0000000106c97580 0x104f7c000 + 30520704
3   libsystem_pthread.dylib       	0x00000001e0b10bfc 0x1e0b0f000 + 7164
4   libsystem_pthread.dylib       	0x00000001e0b19758 0x1e0b0f000 + 42840

Thread 2 name:  Finalizer
Thread 2:
0   libsystem_kernel.dylib        	0x00000001c3622538 0x1c361e000 + 17720
1   NewVisionIT.iOS               	0x0000000106bd4588 0x104f7c000 + 29721992
2   NewVisionIT.iOS               	0x0000000106c4d354 0x104f7c000 + 30217044
3   NewVisionIT.iOS               	0x0000000106c4d1d8 0x104f7c000 + 30216664
4   libsystem_pthread.dylib       	0x00000001e0b10bfc 0x1e0b0f000 + 7164
5   libsystem_pthread.dylib       	0x00000001e0b19758 0x1e0b0f000 + 42840

Thread 3 name:  tid_2d0b
Thread 3:
0   libsystem_pthread.dylib       	0x00000001e0b19744 0x1e0b0f000 + 42820

Thread 4 name:  com.apple.uikit.eventfetch-thread
Thread 4:
0   libsystem_kernel.dylib        	0x00000001c36224fc 0x1c361e000 + 17660
1   libsystem_kernel.dylib        	0x00000001c3621884 0x1c361e000 + 14468
2   CoreFoundation                	0x0000000195aa4eb0 0x195a02000 + 667312
3   CoreFoundation                	0x0000000195a9ed50 0x195a02000 + 642384
4   CoreFoundation                	0x0000000195a9e360 0x195a02000 + 639840
5   Foundation                    	0x0000000196d8bfdc 0x196d84000 + 32732
6   Foundation                    	0x0000000196d8bea8 0x196d84000 + 32424
7   UIKitCore                     	0x00000001985ce12c 0x19794f000 + 13103404
8   Foundation                    	0x0000000196efd32c 0x196d84000 + 1545004
9   libsystem_pthread.dylib       	0x00000001e0b10bfc 0x1e0b0f000 + 7164
10  libsystem_pthread.dylib       	0x00000001e0b19758 0x1e0b0f000 + 42840

Thread 5 name:  tid_1322b
Thread 5:
0   libsystem_pthread.dylib       	0x00000001e0b19744 0x1e0b0f000 + 42820

Thread 6 name:  tid_9a03
Thread 6:
0   libsystem_kernel.dylib        	0x00000001c36470cc 0x1c361e000 + 168140
1   libsystem_pthread.dylib       	0x00000001e0b14434 0x1e0b0f000 + 21556
2   NewVisionIT.iOS               	0x0000000106ca5224 0x104f7c000 + 30577188
3   NewVisionIT.iOS               	0x0000000106cac6f0 0x104f7c000 + 30607088
4   NewVisionIT.iOS               	0x0000000106c44a68 0x104f7c000 + 30181992
5   NewVisionIT.iOS               	0x0000000106c4d354 0x104f7c000 + 30217044
6   NewVisionIT.iOS               	0x0000000106c4d1d8 0x104f7c000 + 30216664
7   libsystem_pthread.dylib       	0x00000001e0b10bfc 0x1e0b0f000 + 7164
8   libsystem_pthread.dylib       	0x00000001e0b19758 0x1e0b0f000 + 42840

Thread 7 name:  Thread Pool Worker
Thread 7:
0   libsystem_kernel.dylib        	0x00000001c3622550 0x1c361e000 + 17744
1   NewVisionIT.iOS               	0x0000000106c45320 0x104f7c000 + 30184224
2   NewVisionIT.iOS               	0x0000000106c4d354 0x104f7c000 + 30217044
3   NewVisionIT.iOS               	0x0000000106c4d1d8 0x104f7c000 + 30216664
4   libsystem_pthread.dylib       	0x00000001e0b10bfc 0x1e0b0f000 + 7164
5   libsystem_pthread.dylib       	0x00000001e0b19758 0x1e0b0f000 + 42840

Thread 8 name:  Timer-Scheduler
Thread 8:
0   libsystem_kernel.dylib        	0x00000001c36470cc 0x1c361e000 + 168140
1   libsystem_pthread.dylib       	0x00000001e0b14434 0x1e0b0f000 + 21556
2   NewVisionIT.iOS               	0x0000000106ca5224 0x104f7c000 + 30577188
3   NewVisionIT.iOS               	0x0000000106c54dcc 0x104f7c000 + 30248396
4   NewVisionIT.iOS               	0x0000000106c54ca4 0x104f7c000 + 30248100
5   NewVisionIT.iOS               	0x0000000106c54ec8 0x104f7c000 + 30248648
6   NewVisionIT.iOS               	0x0000000106c495c0 0x104f7c000 + 30201280
7   NewVisionIT.iOS               	0x0000000106bea5c8 0x104f7c000 + 29812168
8   NewVisionIT.iOS               	0x00000001050b8248 0x104f7c000 + 1294920
9   NewVisionIT.iOS               	0x00000001050b7db4 0x104f7c000 + 1293748
10  NewVisionIT.iOS               	0x00000001050b788c 0x104f7c000 + 1292428
11  NewVisionIT.iOS               	0x00000001050b783c 0x104f7c000 + 1292348
12  NewVisionIT.iOS               	0x00000001050b773c 0x104f7c000 + 1292092
13  NewVisionIT.iOS               	0x00000001050b77e8 0x104f7c000 + 1292264
14  NewVisionIT.iOS               	0x00000001050babd4 0x104f7c000 + 1305556
15  NewVisionIT.iOS               	0x00000001050b1acc 0x104f7c000 + 1268428
16  NewVisionIT.iOS               	0x00000001050af5bc 0x104f7c000 + 1258940
17  NewVisionIT.iOS               	0x00000001050af3bc 0x104f7c000 + 1258428
18  NewVisionIT.iOS               	0x00000001050af340 0x104f7c000 + 1258304
19  NewVisionIT.iOS               	0x00000001050b1c34 0x104f7c000 + 1268788
20  NewVisionIT.iOS               	0x0000000105354b40 0x104f7c000 + 4033344
21  NewVisionIT.iOS               	0x0000000106b84208 0x104f7c000 + 29393416
22  NewVisionIT.iOS               	0x0000000106c1b6f4 0x104f7c000 + 30013172
23  NewVisionIT.iOS               	0x0000000106c20424 0x104f7c000 + 30032932
24  NewVisionIT.iOS               	0x0000000106c4d44c 0x104f7c000 + 30217292
25  NewVisionIT.iOS               	0x0000000106c4d1d8 0x104f7c000 + 30216664
26  libsystem_pthread.dylib       	0x00000001e0b10bfc 0x1e0b0f000 + 7164
27  libsystem_pthread.dylib       	0x00000001e0b19758 0x1e0b0f000 + 42840

Thread 9 name:  tid_6503
Thread 9:
0   libsystem_kernel.dylib        	0x00000001c36470cc 0x1c361e000 + 168140
1   libsystem_pthread.dylib       	0x00000001e0b14434 0x1e0b0f000 + 21556
2   NewVisionIT.iOS               	0x0000000106ca524c 0x104f7c000 + 30577228
3   NewVisionIT.iOS               	0x0000000106c54dcc 0x104f7c000 + 30248396
4   NewVisionIT.iOS               	0x0000000106c54ca4 0x104f7c000 + 30248100
5   NewVisionIT.iOS               	0x0000000106c1362c 0x104f7c000 + 29980204
6   NewVisionIT.iOS               	0x0000000106be9a5c 0x104f7c000 + 29809244
7   NewVisionIT.iOS               	0x00000001050b11b8 0x104f7c000 + 1266104
8   NewVisionIT.iOS               	0x00000001050b1270 0x104f7c000 + 1266288
9   NewVisionIT.iOS               	0x00000001050b0d5c 0x104f7c000 + 1264988
10  NewVisionIT.iOS               	0x00000001050b0db0 0x104f7c000 + 1265072
11  NewVisionIT.iOS               	0x00000001050aa438 0x104f7c000 + 1238072
12  NewVisionIT.iOS               	0x00000001050aa19c 0x104f7c000 + 1237404
13  NewVisionIT.iOS               	0x000000010580bd10 0x104f7c000 + 8977680
14  NewVisionIT.iOS               	0x000000010580bb08 0x104f7c000 + 8977160
15  NewVisionIT.iOS               	0x000000010580ba3c 0x104f7c000 + 8976956
16  NewVisionIT.iOS               	0x00000001064fe0b4 0x104f7c000 + 22552756
17  NewVisionIT.iOS               	0x00000001050b1acc 0x104f7c000 + 1268428
18  NewVisionIT.iOS               	0x00000001050af5bc 0x104f7c000 + 1258940
19  NewVisionIT.iOS               	0x00000001050af3bc 0x104f7c000 + 1258428
20  NewVisionIT.iOS               	0x00000001050af340 0x104f7c000 + 1258304
21  NewVisionIT.iOS               	0x00000001050b1c34 0x104f7c000 + 1268788
22  NewVisionIT.iOS               	0x0000000105354b40 0x104f7c000 + 4033344
23  NewVisionIT.iOS               	0x0000000106b84208 0x104f7c000 + 29393416
24  NewVisionIT.iOS               	0x0000000106c1b6f4 0x104f7c000 + 30013172
25  NewVisionIT.iOS               	0x0000000106c20424 0x104f7c000 + 30032932
26  NewVisionIT.iOS               	0x0000000106c4d44c 0x104f7c000 + 30217292
27  NewVisionIT.iOS               	0x0000000106c4d1d8 0x104f7c000 + 30216664
28  libsystem_pthread.dylib       	0x00000001e0b10bfc 0x1e0b0f000 + 7164
29  libsystem_pthread.dylib       	0x00000001e0b19758 0x1e0b0f000 + 42840

Thread 10:
0   libsystem_pthread.dylib       	0x00000001e0b19744 0x1e0b0f000 + 42820

Thread 11 name:  Thread Pool Worker
Thread 11:
0   libsystem_kernel.dylib        	0x00000001c3622550 0x1c361e000 + 17744
1   NewVisionIT.iOS               	0x0000000106c45320 0x104f7c000 + 30184224
2   NewVisionIT.iOS               	0x0000000106c4d354 0x104f7c000 + 30217044
3   NewVisionIT.iOS               	0x0000000106c4d1d8 0x104f7c000 + 30216664
4   libsystem_pthread.dylib       	0x00000001e0b10bfc 0x1e0b0f000 + 7164
5   libsystem_pthread.dylib       	0x00000001e0b19758 0x1e0b0f000 + 42840

Thread 0 crashed with ARM Thread State (64-bit):
    x0: 0x0000000000000000   x1: 0x0000000000000000   x2: 0x0000000000000000   x3: 0x0000000000000000
    x4: 0x0000000000000000   x5: 0x0000000000989680   x6: 0x0000000000001a00   x7: 0x0000000000000600
    x8: 0x0bf24c9e7c26132f   x9: 0x0bf24c9f7b13ebef  x10: 0x00000000000003e8  x11: 0x0000000000000000
   x12: 0x000000010f1e8c00  x13: 0x0000000107198dfb  x14: 0x00000000000000e0  x15: 0x0000000080000000
   x16: 0x0000000000000148  x17: 0x000000010735f8c0  x18: 0x000000010c6ac4ec  x19: 0x0000000000000006
   x20: 0x0000000000000103  x21: 0x000000010735f9a0  x22: 0x0000000000000000  x23: 0x000000010e014e00
   x24: 0x0000000107198df8  x25: 0x000000016ae811f0  x26: 0x0000000000000002  x27: 0x0000000106f12d30
   x28: 0x0000000000ffffff   fp: 0x000000016ae803b0   lr: 0x00000001e0b11a9c
    sp: 0x000000016ae80390   pc: 0x00000001c3647334 cpsr: 0x40000000
   esr: 0x56000080  Address size fault

Binary Images:
0x104f7c000 - 0x106da7fff NewVisionIT.iOS arm64  <def53f5fee1b320aae1596b6650c5bec> /var/containers/Bundle/Application/02239B46-30E2-4BD0-9935-76DBF92541F1/NewVisionIT.iOS.app/NewVisionIT.iOS
0x1072b0000 - 0x107323fff dyld arm64e  <65bac7abef933e93b5640506d0e36590> /usr/lib/dyld
0x10910c000 - 0x109117fff libobjc-trampolines.dylib arm64e  <26cb4bb90880358ba280192f8ed6d0ad> /usr/lib/libobjc-trampolines.dylib
0x195714000 - 0x195758fff libdispatch.dylib arm64e  <daf300624c853b92b15950602a0c9d97> /usr/lib/system/libdispatch.dylib
0x195759000 - 0x195795fff libdyld.dylib arm64e  <e574a3659878348a8e8491e163cfc128> /usr/lib/system/libdyld.dylib
0x195796000 - 0x195a01fff libicucore.A.dylib arm64e  <a5ab8a878dd03b00b8c58dc98ac1fb99> /usr/lib/libicucore.A.dylib
0x195a02000 - 0x195dc1fff CoreFoundation arm64e  <4fbdf167161a324ca233d516922c67e5> /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
0x195dc2000 - 0x195f74fff CoreServices arm64e  <46bbb0a72281367ab7c09ce200dfdf86> /System/Library/Frameworks/CoreServices.framework/CoreServices
0x195f75000 - 0x195fbcfff WirelessDiagnostics arm64e  <97df83a096643d9ca2595ab3d30010ea> /System/Library/PrivateFrameworks/WirelessDiagnostics.framework/WirelessDiagnostics
0x195fbd000 - 0x196039fff SystemConfiguration arm64e  <d379b97151cd33938d0f5bda7a431328> /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration
0x19603a000 - 0x19612ffff CoreTelephony arm64e  <85c3411b900f357f88f819c5b49cf365> /System/Library/Frameworks/CoreTelephony.framework/CoreTelephony
0x196130000 - 0x1965c2fff CFNetwork arm64e  <04a7e31d376b37198e587bbe0fe8ee51> /System/Library/Frameworks/CFNetwork.framework/CFNetwork
0x1965c3000 - 0x196d0efff libnetwork.dylib arm64e  <83ca70ba608e3157a1f0903703ceb78d> /usr/lib/libnetwork.dylib
0x196d0f000 - 0x196d83fff Accounts arm64e  <91c28d11436a3caeb988e3040f553391> /System/Library/Frameworks/Accounts.framework/Accounts
0x196d84000 - 0x197039fff Foundation arm64e  <0d9893a458043f0dbb3f73989ea36ad3> /System/Library/Frameworks/Foundation.framework/Foundation
0x19703a000 - 0x19739cfff ImageIO arm64e  <e1ef876fb8643ccdaaced226f90b9f62> /System/Library/Frameworks/ImageIO.framework/ImageIO
0x19739d000 - 0x1973b5fff libCGInterfaces.dylib arm64e  <8f8fcce1d7a13d21a6bf7764eeeb7b79> /System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/Libraries/libCGInterfaces.dylib
0x1973b6000 - 0x19794efff CoreGraphics arm64e  <2f7f6ee8635c332abac3efda4894c7e2> /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
0x19794f000 - 0x198d5afff UIKitCore arm64e  <33b02ab55daf32498dc65872df830ec5> /System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore
0x198d5b000 - 0x198d79fff libAccessibility.dylib arm64e  <ab3dbae1370d3cc696ba51cabe774f49> /usr/lib/libAccessibility.dylib
0x198d7a000 - 0x19900efff QuartzCore arm64e  <4a41f8af4c323302bffc377812960921> /System/Library/Frameworks/QuartzCore.framework/QuartzCore
0x19900f000 - 0x199079fff BackBoardServices arm64e  <1fef1d7eba033f12b7365af97e1ffc93> /System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices
0x19907a000 - 0x199101fff TextInput arm64e  <6783ec80fd23331f9584c5b0f2ed1380> /System/Library/PrivateFrameworks/TextInput.framework/TextInput
0x199102000 - 0x19916afff libusrtcp.dylib arm64e  <080671b68c363e1fb35a6665fc0e0232> /usr/lib/libusrtcp.dylib
0x19916b000 - 0x199524fff AppleMediaServices arm64e  <1a161a667a8c339493640dac1bbd96ba> /System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices
0x199525000 - 0x199687fff libswiftFoundation.dylib arm64e  <b8355af4f9e339d68a90f63ae305572c> /usr/lib/swift/libswiftFoundation.dylib
0x199688000 - 0x199ac9fff libswiftCore.dylib arm64e  <371457f70ecd3a139bd9a9de3351129f> /usr/lib/swift/libswiftCore.dylib
0x199aca000 - 0x199ae6fff UIKitServices arm64e  <3471d8dcbf1d3110b129bcf2c1bc36d7> /System/Library/PrivateFrameworks/UIKitServices.framework/UIKitServices
0x199ae7000 - 0x199c3cfff Preferences arm64e  <303526218e5333fabb218164ab50d4ae> /System/Library/PrivateFrameworks/Preferences.framework/Preferences
0x199c3d000 - 0x199e48fff ContactsUI arm64e  <34505f6e92f33ada9d7acd53e66c71dd> /System/Library/Frameworks/ContactsUI.framework/ContactsUI
0x199e49000 - 0x199ffefff CoreText arm64e  <3fb1158c6de33d9dbf8c51c0b85b7215> /System/Library/Frameworks/CoreText.framework/CoreText
0x199fff000 - 0x19a018fff ExtensionKit arm64e  <9b482c1605543e5484f596cca27a5697> /System/Library/PrivateFrameworks/ExtensionKit.framework/ExtensionKit
0x19a02f000 - 0x19a0b2fff BaseBoard arm64e  <ddf259ac1f60332b9e189ee643049fc2> /System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard
0x19a0b3000 - 0x19a2fefff CoreDuet arm64e  <c1a013e6d97b37b583ad8c484c8512a0> /System/Library/PrivateFrameworks/CoreDuet.framework/CoreDuet
0x19a2ff000 - 0x19a458fff Contacts arm64e  <8ac22bf4a74d3478bb7b67b5ac2398d3> /System/Library/Frameworks/Contacts.framework/Contacts
0x19a459000 - 0x19b9bdfff GeoServices arm64e  <d7cabd2a82e03fa39bba4fd6f6462ce5> /System/Library/PrivateFrameworks/GeoServices.framework/GeoServices
0x19b9be000 - 0x19ba54fff CoreLocation arm64e  <478b7a67d7013e1e887c0576f04196e6> /System/Library/Frameworks/CoreLocation.framework/CoreLocation
0x19ba55000 - 0x19bbf6fff CloudKit arm64e  <7d1418c47973307ca780a47b61c14a34> /System/Library/Frameworks/CloudKit.framework/CloudKit
0x19bbf7000 - 0x19bf6bfff CoreData arm64e  <e9b054793d07390cbd3673eedb2b1f75> /System/Library/Frameworks/CoreData.framework/CoreData
0x19cd07000 - 0x19cd11fff libswiftCoreGraphics.dylib arm64e  <bfa50cd9719533b895e635d646102e70> /usr/lib/swift/libswiftCoreGraphics.dylib
0x19cd12000 - 0x19cd51fff AppSupport arm64e  <278b64ad1ce33739b8680ffc6b16f3fd> /System/Library/PrivateFrameworks/AppSupport.framework/AppSupport
0x19cd52000 - 0x19ce77fff ManagedConfiguration arm64e  <611487e209d73fa89d6f9b9f79c23021> /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration
0x19ce78000 - 0x19cee6fff IMFoundation arm64e  <5be95543f917352cb54b37a9f63cd33e> /System/Library/PrivateFrameworks/IMFoundation.framework/IMFoundation
0x19cee7000 - 0x19cff4fff IDS arm64e  <07d02af11ca03b1082ff798585f5135c> /System/Library/PrivateFrameworks/IDS.framework/IDS
0x19cff5000 - 0x19d147fff Security arm64e  <f7ddff4fa4f339dfb4fb414e13a49b71> /System/Library/Frameworks/Security.framework/Security
0x19d148000 - 0x19d529fff MediaPlayer arm64e  <928360c7f723391fa70e3a1cff21a51c> /System/Library/Frameworks/MediaPlayer.framework/MediaPlayer
0x19d52a000 - 0x19d541fff AudioSession arm64e  <b5867acdfe45334fbc2dc3029b5c64b4> /System/Library/PrivateFrameworks/AudioSession.framework/AudioSession
0x19d542000 - 0x19d6ecfff AVFCore arm64e  <4d251ba117003e9ab4279567dc72d529> /System/Library/PrivateFrameworks/AVFCore.framework/AVFCore
0x19d6ed000 - 0x19dc89fff Intents arm64e  <12de7cdc4499382e94715882cb23e157> /System/Library/Frameworks/Intents.framework/Intents
0x19dc8a000 - 0x19dcd8fff TextInputUI arm64e  <b15285104c3937e68ab97905c6b994c7> /System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI
0x19dcd9000 - 0x19dfeafff CoreImage arm64e  <cf56bcb19ee3392d8922c8894c9f94c7> /System/Library/Frameworks/CoreImage.framework/CoreImage
0x19dfeb000 - 0x19e0a8fff ColorSync arm64e  <de843ac9c945370b89d709c4814e61bb> /System/Library/PrivateFrameworks/ColorSync.framework/ColorSync
0x19e0a9000 - 0x19e0e4fff CoreVideo arm64e  <b448328e46e3382999ac35e14541ddf7> /System/Library/Frameworks/CoreVideo.framework/CoreVideo
0x19e0e5000 - 0x19e90dfff MediaToolbox arm64e  <17b3c973ec673d379dbd1317c600174b> /System/Library/Frameworks/MediaToolbox.framework/MediaToolbox
0x19e90e000 - 0x19ea0ffff CoreMedia arm64e  <d76d711db7d63a3987cbc8f379203c75> /System/Library/Frameworks/CoreMedia.framework/CoreMedia
0x19ea10000 - 0x19ec80fff AudioToolbox arm64e  <0a7f10d4561c32d48a99cfa7907d3b7a> /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox
0x19ec81000 - 0x19ecd1fff CoreHaptics arm64e  <d1846ddf74e939c7ac8e04773c55301d> /System/Library/Frameworks/CoreHaptics.framework/CoreHaptics
0x19ecd2000 - 0x19ed31fff UserActivity arm64e  <1c29d8ce109131e4a625ed23d14c9c25> /System/Library/PrivateFrameworks/UserActivity.framework/UserActivity
0x19ed32000 - 0x19ee3bfff UIFoundation arm64e  <5f8b069e7df837cca2402ad838c0b414> /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation
0x19ee3c000 - 0x19ee61fff libsystem_info.dylib arm64e  <7bba4c4822da3fb7b1e8d2d6e91681b7> /usr/lib/system/libsystem_info.dylib
0x19ee62000 - 0x19eee1fff libsystem_c.dylib arm64e  <3c5017016b013e70a81676794ea12708> /usr/lib/system/libsystem_c.dylib
0x19eee2000 - 0x19ef2cfff RunningBoardServices arm64e  <3e5f33aa70ff32d1a475bd9356a2af78> /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices
0x19ef2d000 - 0x19fffcfff JavaScriptCore arm64e  <74545bac15ff320da90b8f89f75e39c1> /System/Library/Frameworks/JavaScriptCore.framework/JavaScriptCore
0x1a05ab000 - 0x1a0639fff ContactsFoundation arm64e  <5847c7c551b63a249c22169e8207be80> /System/Library/PrivateFrameworks/ContactsFoundation.framework/ContactsFoundation
0x1a063a000 - 0x1a087cfff HealthKit arm64e  <e38fa61a8b6e3cc6803229aca5af2098> /System/Library/Frameworks/HealthKit.framework/HealthKit
0x1a087d000 - 0x1a089ffff ProactiveEventTracker arm64e  <48189564b4af35d3be61876d36e7f82c> /System/Library/PrivateFrameworks/ProactiveEventTracker.framework/ProactiveEventTracker
0x1a08a0000 - 0x1a08eafff Lexicon arm64e  <ecee052ae6f53dfe881e400acea9fee8> /System/Library/PrivateFrameworks/Lexicon.framework/Lexicon
0x1a08eb000 - 0x1a0954fff PersonalizationPortrait arm64e  <3e0621fca60137bb9ab2583800183767> /System/Library/PrivateFrameworks/PersonalizationPortrait.framework/PersonalizationPortrait
0x1a0955000 - 0x1a09a4fff CoreDuetContext arm64e  <076cc8cef7373eeebc980864aa8344ea> /System/Library/PrivateFrameworks/CoreDuetContext.framework/CoreDuetContext
0x1a09a5000 - 0x1a0a50fff IOKit arm64e  <4921ff204f963660b07a7f34fb58e5a3> /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
0x1a0a51000 - 0x1a0a5ffff DataMigration arm64e  <ca1f27e516753a33adadd966bde5b9e6> /System/Library/PrivateFrameworks/DataMigration.framework/DataMigration
0x1a0a60000 - 0x1a0abbfff SpringBoardServices arm64e  <030c7e75a08635a3a628c6c3b8f64d03> /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices
0x1a0abc000 - 0x1a0acdfff ContextKit arm64e  <d5f880d99ff53155bb26e47930189361> /System/Library/PrivateFrameworks/ContextKit.framework/ContextKit
0x1a0ace000 - 0x1a0d41fff CoreMotion arm64e  <9b26d7db372a351580b540af68e75754> /System/Library/Frameworks/CoreMotion.framework/CoreMotion
0x1a0d42000 - 0x1a0e7ffff EventKit arm64e  <daa0d5b82652379484caea0ed21673a4> /System/Library/Frameworks/EventKit.framework/EventKit
0x1a13d3000 - 0x1a167cfff MediaRemote arm64e  <b850c411e0d73ff5893c3af70282f177> /System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote
0x1a167d000 - 0x1a1827fff CoreUtils arm64e  <d0c2761a316c36558f11006ffa6f081f> /System/Library/PrivateFrameworks/CoreUtils.framework/CoreUtils
0x1a1828000 - 0x1a183dfff FamilyCircle arm64e  <1b966d90bf0c3c20bbb3a4fa56b5bd17> /System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle
0x1a183e000 - 0x1a18aafff CoreSpotlight arm64e  <ab5c8a8e08c53652a25487e073550554> /System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight
0x1a1bf9000 - 0x1a1dcbfff AssistantServices arm64e  <25f0850bbc573496b988caacecfcc7ae> /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices
0x1a1dcc000 - 0x1a1e90fff CoreUI arm64e  <166a77aadb8e389e8a94d9caa55f6efb> /System/Library/PrivateFrameworks/CoreUI.framework/CoreUI
0x1a1e91000 - 0x1a1edefff SafariSafeBrowsing arm64e  <045e0cc95bd33db5830a4400175ce6d7> /System/Library/PrivateFrameworks/SafariSafeBrowsing.framework/SafariSafeBrowsing
0x1a1edf000 - 0x1a26b8fff WebKit arm64e  <9f7b0b3b7f333f7f883e7b2ee83f42fb> /System/Library/Frameworks/WebKit.framework/WebKit
0x1a26b9000 - 0x1a4c58fff WebCore arm64e  <6ef2878d48893fb0ba38781b25c9d587> /System/Library/PrivateFrameworks/WebCore.framework/WebCore
0x1a4c59000 - 0x1a4cb7fff libMobileGestalt.dylib arm64e  <e3d1b8d0cf153d48a14b6bebbe344f82> /usr/lib/libMobileGestalt.dylib
0x1a4cb8000 - 0x1a4cd3fff CommonUtilities arm64e  <c13f8ed7ae62314eae95731f263f1320> /System/Library/PrivateFrameworks/CommonUtilities.framework/CommonUtilities
0x1a4cd4000 - 0x1a4e39fff IDSFoundation arm64e  <7ad6c2866a4b3f4baaa11318b4014232> /System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation
0x1a4e3a000 - 0x1a4f3afff IMSharedUtilities arm64e  <7b7d8909131f30088dfca0c3ed4c4f02> /System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities
0x1a4f3b000 - 0x1a4fe3fff CoreSuggestions arm64e  <f1ef331e869f3224bacc8ae6719bda35> /System/Library/PrivateFrameworks/CoreSuggestions.framework/CoreSuggestions
0x1a4fe4000 - 0x1a5080fff AddressBookLegacy arm64e  <ad8079c3bedc355db3d2282ae33dd728> /System/Library/PrivateFrameworks/AddressBookLegacy.framework/AddressBookLegacy
0x1a5081000 - 0x1a50b2fff UserNotifications arm64e  <c16a26ec816f364cadf5107d1538ff10> /System/Library/Frameworks/UserNotifications.framework/UserNotifications
0x1a50b3000 - 0x1a513cfff FrontBoardServices arm64e  <3072e730ae783201b7147712d4f1fc2f> /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices
0x1a513d000 - 0x1a5160fff libsystem_malloc.dylib arm64e  <716786f4da963293bb007ed833124dea> /usr/lib/system/libsystem_malloc.dylib
0x1a5161000 - 0x1a5426fff MapKit arm64e  <8517a7e664c738e3bd1277f0b8a83f09> /System/Library/Frameworks/MapKit.framework/MapKit
0x1a5427000 - 0x1a5bc6fff VectorKit arm64e  <9e6b10f2cb503148b850615ffd48985d> /System/Library/PrivateFrameworks/VectorKit.framework/VectorKit
0x1a5bc7000 - 0x1a5c55fff AuthKit arm64e  <d6d92342caae3c57a582d22f8a3c5ce9> /System/Library/PrivateFrameworks/AuthKit.framework/AuthKit
0x1a5c56000 - 0x1a5ce7fff AppleAccount arm64e  <00c881704e2b3d56b5299e2f0c900f44> /System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount
0x1a5ce8000 - 0x1a5f4ffff AudioToolboxCore arm64e  <9ff4a959d0b63cf486406331d18baae8> /System/Library/PrivateFrameworks/AudioToolboxCore.framework/AudioToolboxCore
0x1a5f83000 - 0x1a6255fff StoreServices arm64e  <067804da7d8b33a6860cc9cd8f23557c> /System/Library/PrivateFrameworks/StoreServices.framework/StoreServices
0x1a6256000 - 0x1a63e5fff Sharing arm64e  <3139874d2a5d370293ee7cd5caf18e60> /System/Library/PrivateFrameworks/Sharing.framework/Sharing
0x1a63e6000 - 0x1a6486fff ShareSheet arm64e  <bd85c605554e345f88bb5a4cd380b2ca> /System/Library/PrivateFrameworks/ShareSheet.framework/ShareSheet
0x1a6487000 - 0x1a654afff CoreParsec arm64e  <370fd2a149733c6b84c69bf6e06b92dd> /System/Library/PrivateFrameworks/CoreParsec.framework/CoreParsec
0x1a654b000 - 0x1a6592fff PhotoFoundation arm64e  <19ec22cc329334b3802133c8a796b9bf> /System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation
0x1a6593000 - 0x1a67d1fff Photos arm64e  <f054493bdff036cfa16f3fad105684c8> /System/Library/Frameworks/Photos.framework/Photos
0x1a67d2000 - 0x1a6ef2fff PhotoLibraryServices arm64e  <9d391596c025363faf98c84ad97803d8> /System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PhotoLibraryServices
0x1a6ef3000 - 0x1a6fb2fff AssetsLibraryServices arm64e  <399d1b28b168305189ce90ac75144729> /System/Library/PrivateFrameworks/AssetsLibraryServices.framework/AssetsLibraryServices
0x1a6fb3000 - 0x1a7002fff MobileBackup arm64e  <453890c85ab83e03a787d26120f9e0e4> /System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup
0x1a7003000 - 0x1a7016fff MSUDataAccessor arm64e  <ce5a5e805b7938d7910f510722850439> /System/Library/PrivateFrameworks/MSUDataAccessor.framework/MSUDataAccessor
0x1a7017000 - 0x1a703efff MobileAsset arm64e  <dd5a75980f8b3ee389c619afa3f2286d> /System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset
0x1a703f000 - 0x1a704efff libsystem_networkextension.dylib arm64e  <364c51a986e433ba96d14a937172acd9> /usr/lib/system/libsystem_networkextension.dylib
0x1a704f000 - 0x1a7296fff NetworkExtension arm64e  <50bb1798909730cc985d0cd7f7fceb10> /System/Library/Frameworks/NetworkExtension.framework/NetworkExtension
0x1a7297000 - 0x1a72cdfff Trial arm64e  <9481a13482a23f658b59e95a0547ad8f> /System/Library/PrivateFrameworks/Trial.framework/Trial
0x1a72ce000 - 0x1a7b4dfff CoreML arm64e  <1f259375db02310da05342fbd8165188> /System/Library/Frameworks/CoreML.framework/CoreML
0x1a7b4e000 - 0x1a82c1fff Espresso arm64e  <cbfeed0492f53b9aac7a225790314458> /System/Library/PrivateFrameworks/Espresso.framework/Espresso
0x1a82c2000 - 0x1a83cafff VideoToolbox arm64e  <59d714b0a65e36eab19e45ea6a3bb87a> /System/Library/Frameworks/VideoToolbox.framework/VideoToolbox
0x1a83cb000 - 0x1a8413fff OnBoardingKit arm64e  <0627db26ffec3dfe99f94278f74ccd7f> /System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit
0x1a8414000 - 0x1a8508fff AccessibilityUtilities arm64e  <3cc713c3c30c3a848bc3b81e137801eb> /System/Library/PrivateFrameworks/AccessibilityUtilities.framework/AccessibilityUtilities
0x1a8509000 - 0x1a851afff AXCoreUtilities arm64e  <92334abbfaed374c91da5518f67bfa10> /System/Library/PrivateFrameworks/AXCoreUtilities.framework/AXCoreUtilities
0x1a851b000 - 0x1a8a9bfff PhotosUI arm64e  <3294ff29d56c3d5980d2257936b80913> /System/Library/Frameworks/PhotosUI.framework/PhotosUI
0x1a8a9c000 - 0x1a9365fff PhotosUICore arm64e  <ed666cd0a01b380d8fcf7a60c941a87d> /System/Library/PrivateFrameworks/PhotosUICore.framework/PhotosUICore
0x1a9366000 - 0x1a94dafff Montreal arm64e  <7f993e75ec703c5fb56fea9ec4cf977b> /System/Library/PrivateFrameworks/Montreal.framework/Montreal
0x1a94db000 - 0x1a95eefff LanguageModeling arm64e  <d2343e512d0e3b5cbe7ae1c871c7232a> /System/Library/PrivateFrameworks/LanguageModeling.framework/LanguageModeling
0x1a95ef000 - 0x1a95f7fff InternationalSupport arm64e  <130682a1171631358b7b266a5af61a8c> /System/Library/PrivateFrameworks/InternationalSupport.framework/InternationalSupport
0x1a95f8000 - 0x1a984afff iTunesCloud arm64e  <c340b2a8dc5e30899fe03e178b942761> /System/Library/PrivateFrameworks/iTunesCloud.framework/iTunesCloud
0x1a99a7000 - 0x1a9a50fff CalendarDatabase arm64e  <c5e1c174b91c3ae09302c644a7d10f4f> /System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase
0x1a9a9f000 - 0x1a9b82fff LinkPresentation arm64e  <e4a335042bd23a588379387cc403f9f7> /System/Library/Frameworks/LinkPresentation.framework/LinkPresentation
0x1a9b83000 - 0x1a9cc4fff Combine arm64e  <ea0501ab359636cf93aa1408de43844c> /System/Library/Frameworks/Combine.framework/Combine
0x1a9d51000 - 0x1a9d62fff UniformTypeIdentifiers arm64e  <995c315262ee3947b8284ae1cf3ab125> /System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers
0x1a9d63000 - 0x1a9de4fff CloudDocs arm64e  <e80987779e6a38008477b92f32469012> /System/Library/PrivateFrameworks/CloudDocs.framework/CloudDocs
0x1aa321000 - 0x1aa365fff MediaServices arm64e  <a7d9ab2067a03c5db329a15a3e719499> /System/Library/PrivateFrameworks/MediaServices.framework/MediaServices
0x1aa366000 - 0x1aa4f0fff SearchFoundation arm64e  <6f77af23a360368b82bceb65e749e284> /System/Library/PrivateFrameworks/SearchFoundation.framework/SearchFoundation
0x1aa4f1000 - 0x1aa54bfff WebBookmarks arm64e  <3cc80385ece13879809db1354bcdddd7> /System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks
0x1aa5ca000 - 0x1aa601fff libobjc.A.dylib arm64e  <266e9238111c3f2da0d2604474e3cdc4> /usr/lib/libobjc.A.dylib
0x1aa602000 - 0x1aa663fff LoggingSupport arm64e  <20a4e30f1b323be595a0bcd9f802ee15> /System/Library/PrivateFrameworks/LoggingSupport.framework/LoggingSupport
0x1aa664000 - 0x1aa6bffff libc++.1.dylib arm64e  <9aa8a1f311a73857b27476e140edd0b6> /usr/lib/libc++.1.dylib
0x1aa6c0000 - 0x1aa6d9fff libc++abi.dylib arm64e  <f6119d353d8837d2aa8e88dfc6f2a00d> /usr/lib/libc++abi.dylib
0x1aa6da000 - 0x1aa71bfff SetupAssistant arm64e  <d9c5cfb51ef83497be336ada66f6c6cd> /System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant
0x1aa86d000 - 0x1aa8affff CoreAutoLayout arm64e  <ace17dcf0bbd3de4847ac67f55422625> /System/Library/PrivateFrameworks/CoreAutoLayout.framework/CoreAutoLayout
0x1aa8b0000 - 0x1aaa0cfff Network arm64e  <64059de5ad873ac993cb8eaf0600b881> /System/Library/Frameworks/Network.framework/Network
0x1aaa0d000 - 0x1aaa43fff MobileKeyBag arm64e  <26d4b16a85363a36888d778ba9b9cb98> /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag
0x1aac74000 - 0x1aac86fff BaseBoardUI arm64e  <e8560d052d663314a35f6b158fce4f9d> /System/Library/PrivateFrameworks/BaseBoardUI.framework/BaseBoardUI
0x1aac87000 - 0x1aad35fff libvDSP.dylib arm64e  <381d831ab9be35b6aeff8ac003b21e24> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libvDSP.dylib
0x1aad36000 - 0x1aad69fff libAudioToolboxUtility.dylib arm64e  <afaf628ed19b33d687114163a8b9031d> /usr/lib/libAudioToolboxUtility.dylib
0x1aaf3d000 - 0x1aafc8fff CoreNLP arm64e  <bb3e346ae91a31cf9b4555e1c648edbe> /System/Library/PrivateFrameworks/CoreNLP.framework/CoreNLP
0x1aafc9000 - 0x1ab0defff FileProvider arm64e  <5118c253d0fb3a58a39a6e6c25ddbf3f> /System/Library/Frameworks/FileProvider.framework/FileProvider
0x1ab0df000 - 0x1ab0f0fff BiomeStorage arm64e  <05c05dcdf26b34a798f4013fb3febd07> /System/Library/PrivateFrameworks/BiomeStorage.framework/BiomeStorage
0x1ab0f1000 - 0x1ab109fff libswiftDispatch.dylib arm64e  <e2ba45995ccb36b6900451b6313786fe> /usr/lib/swift/libswiftDispatch.dylib
0x1ab10a000 - 0x1ab13ffff DataDetectorsCore arm64e  <6dc0f9a937473bea8ccdd67b4ff52453> /System/Library/PrivateFrameworks/DataDetectorsCore.framework/DataDetectorsCore
0x1ab140000 - 0x1ab1dcfff Symbolication arm64e  <aaa210cc0ba132e6a7a9051ba7daba6a> /System/Library/PrivateFrameworks/Symbolication.framework/Symbolication
0x1ab1dd000 - 0x1ab1ebfff CrashReporterSupport arm64e  <cbbd8dbb2d463486a7f790ad9576fc28> /System/Library/PrivateFrameworks/CrashReporterSupport.framework/CrashReporterSupport
0x1ab24d000 - 0x1ab31ffff TelephonyUtilities arm64e  <be8ab028bdf13f2b9d7cba911e997349> /System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities
0x1ab357000 - 0x1ab544fff MPSNeuralNetwork arm64e  <32c3b58dae033f8287e6f950122a5415> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNeuralNetwork.framework/MPSNeuralNetwork
0x1ab545000 - 0x1ab59afff MPSCore arm64e  <596076932b2a37acabf5a85b7818ff54> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSCore.framework/MPSCore
0x1ab6f5000 - 0x1ab75efff CalendarFoundation arm64e  <0edad51da34a3499b87de213e80604d7> /System/Library/PrivateFrameworks/CalendarFoundation.framework/CalendarFoundation
0x1ab7bf000 - 0x1ab8a8fff NLP arm64e  <964c89761f043ccea6590be906f63b7f> /System/Library/PrivateFrameworks/NLP.framework/NLP
0x1ab8a9000 - 0x1ab8d0fff AppSupportUI arm64e  <e72a093184263af795e4b44e490cbb69> /System/Library/PrivateFrameworks/AppSupportUI.framework/AppSupportUI
0x1ab8da000 - 0x1ab92dfff FTServices arm64e  <393cdc763a1f3391a66afd847a168a8f> /System/Library/PrivateFrameworks/FTServices.framework/FTServices
0x1ab92e000 - 0x1ab9e0fff libboringssl.dylib arm64e  <0a4ed384db6d360399b21f201ea3677a> /usr/lib/libboringssl.dylib
0x1ab9e1000 - 0x1ab9f7fff ProtocolBuffer arm64e  <8b5794c1afa43f84a25492cf27a63f2a> /System/Library/PrivateFrameworks/ProtocolBuffer.framework/ProtocolBuffer
0x1ab9f8000 - 0x1abaf8fff AVKit arm64e  <6e5fbf97f76c31448a6194c291a1af4d> /System/Library/Frameworks/AVKit.framework/AVKit
0x1abc66000 - 0x1abc75fff AssertionServices arm64e  <7acbf04dd3df3d7bb1e0fcffc76e96e5> /System/Library/PrivateFrameworks/AssertionServices.framework/AssertionServices
0x1abcf3000 - 0x1abdcefff Metal arm64e  <e82f8748f9503e3d81a377ceaa568192> /System/Library/Frameworks/Metal.framework/Metal
0x1abdcf000 - 0x1abf25fff MediaExperience arm64e  <ac8f5a4d78b0389db1cdb57c79657d50> /System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience
0x1abf26000 - 0x1ac32ffff VideoProcessing arm64e  <ccf94a6722493d58be1bdb03f3f7e7c9> /System/Library/PrivateFrameworks/VideoProcessing.framework/VideoProcessing
0x1ac330000 - 0x1ac346fff libsystem_trace.dylib arm64e  <8fc630a0bd603c48a6e04b52ad7c171b> /usr/lib/system/libsystem_trace.dylib
0x1ac347000 - 0x1ac378fff CoreServicesInternal arm64e  <270e4b3d8a7c36678c9e5c46b9573ca0> /System/Library/PrivateFrameworks/CoreServicesInternal.framework/CoreServicesInternal
0x1ac379000 - 0x1ac3e8fff SafariCore arm64e  <69d4c102505a335e8646ee981d204640> /System/Library/PrivateFrameworks/SafariCore.framework/SafariCore
0x1ac3e9000 - 0x1ac61cfff SafariShared arm64e  <351ccc97623036b281a872e6f28abe60> /System/Library/PrivateFrameworks/SafariShared.framework/SafariShared
0x1ad016000 - 0x1ad08efff SAObjects arm64e  <d748702c98703400b0de4873aa374063> /System/Library/PrivateFrameworks/SAObjects.framework/SAObjects
0x1ad08f000 - 0x1ad0d8fff VoiceServices arm64e  <1eecc8ff32563484989aa4e4a130250e> /System/Library/PrivateFrameworks/VoiceServices.framework/VoiceServices
0x1ad0d9000 - 0x1ad0e1fff GraphicsServices arm64e  <bacaa05dfc9a36668498ad9dc1ef3095> /System/Library/PrivateFrameworks/GraphicsServices.framework/GraphicsServices
0x1ad0e2000 - 0x1ad134fff DeviceManagement arm64e  <d7854f4d3d663eda8e26885a938ad35c> /System/Library/PrivateFrameworks/DeviceManagement.framework/DeviceManagement
0x1ad135000 - 0x1ad2aefff Translation arm64e  <2d2c3e280e333437b6c41939ddeadeab> /System/Library/PrivateFrameworks/Translation.framework/Translation
0x1ad2af000 - 0x1ad2c3fff PowerLog arm64e  <ed9a9e0d598130e2b67a8981e5cfe4c7> /System/Library/PrivateFrameworks/PowerLog.framework/PowerLog
0x1ad2c4000 - 0x1ad2ebfff DuetActivityScheduler arm64e  <806f8e0ccd8537bc9317c7348c8484ab> /System/Library/PrivateFrameworks/DuetActivityScheduler.framework/DuetActivityScheduler
0x1aed86000 - 0x1af02bfff Vision arm64e  <832137c30144368386b4271c91b78098> /System/Library/Frameworks/Vision.framework/Vision
0x1af086000 - 0x1af0f0fff ProactiveSupport arm64e  <451e0df122653aa1b6e59a6d87c661ab> /System/Library/PrivateFrameworks/ProactiveSupport.framework/ProactiveSupport
0x1af11c000 - 0x1af13bfff ApplePushService arm64e  <0f7f35b4f55f35079234005cf7c4b057> /System/Library/PrivateFrameworks/ApplePushService.framework/ApplePushService
0x1af13c000 - 0x1af165fff BoardServices arm64e  <7b590d67d5d83de38ac6bcae4ef8ec89> /System/Library/PrivateFrameworks/BoardServices.framework/BoardServices
0x1af2da000 - 0x1af30afff libncurses.5.4.dylib arm64e  <f834979dadd4397291aef23d65cd8bcc> /usr/lib/libncurses.5.4.dylib
0x1af30b000 - 0x1af34afff OSAnalytics arm64e  <c7d112e1689d3805a0e0edabf9e6310f> /System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics
0x1af34b000 - 0x1af3a6fff CoreBluetooth arm64e  <f6f9fa4994f73e5497e127d5a517b006> /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
0x1af59a000 - 0x1af5ddfff TemplateKit arm64e  <b6f43561687335d8b1a7bdd90abeb299> /System/Library/PrivateFrameworks/TemplateKit.framework/TemplateKit
0x1af5de000 - 0x1af61cfff MobileInstallation arm64e  <8c1f341bb2933251acb61b68fd2703d7> /System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation
0x1af61d000 - 0x1af6aafff libTelephonyUtilDynamic.dylib arm64e  <6b39fd863eee325280eaafb38a59e3c4> /usr/lib/libTelephonyUtilDynamic.dylib
0x1af6ab000 - 0x1af718fff NanoRegistry arm64e  <b06179bc662b3265855d9cd8f9946298> /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry
0x1af7f7000 - 0x1af813fff CoreMaterial arm64e  <2d3a44a83c1e303f80679aab261d3832> /System/Library/PrivateFrameworks/CoreMaterial.framework/CoreMaterial
0x1af88a000 - 0x1afa0ffff libsqlite3.dylib arm64e  <bfd2376f2e6e33fda5c2413484cd6d51> /usr/lib/libsqlite3.dylib
0x1afa10000 - 0x1afad5fff AVFCapture arm64e  <cf7ea5374a8c32a2992a4a18f31ad11d> /System/Library/PrivateFrameworks/AVFCapture.framework/AVFCapture
0x1afad6000 - 0x1afe21fff CMCapture arm64e  <cd4a35ca881e3a2099867e2a445a9f8c> /System/Library/PrivateFrameworks/CMCapture.framework/CMCapture
0x1affdc000 - 0x1b0250fff MobileSpotlightIndex arm64e  <ae83fb0fd54f3a509460595f004bd8ac> /System/Library/PrivateFrameworks/MobileSpotlightIndex.framework/MobileSpotlightIndex
0x1b0680000 - 0x1b068afff libsystem_notify.dylib arm64e  <108b5014f4a63f24ab7141de0b9121ef> /usr/lib/system/libsystem_notify.dylib
0x1b068b000 - 0x1b06cefff CryptoTokenKit arm64e  <5d5d3968cda6341cbc893038b12b313f> /System/Library/Frameworks/CryptoTokenKit.framework/CryptoTokenKit
0x1b0739000 - 0x1b07acfff libcorecrypto.dylib arm64e  <b80885becfb33d59a43ade3b984473c2> /usr/lib/system/libcorecrypto.dylib
0x1b07ad000 - 0x1b07d0fff UserManagement arm64e  <8b1ffed0dab631e38cb779a97d908db0> /System/Library/PrivateFrameworks/UserManagement.framework/UserManagement
0x1b08a8000 - 0x1b08c2fff libsystem_asl.dylib arm64e  <e2e9c5299508354da9744e86fd6bafd3> /usr/lib/system/libsystem_asl.dylib
0x1b08c3000 - 0x1b08e8fff AppSSO arm64e  <bb6f1ef126753b62b7650d70b211e9c5> /System/Library/PrivateFrameworks/AppSSO.framework/AppSSO
0x1b08e9000 - 0x1b0909fff SharedWebCredentials arm64e  <f0e26b3411d6371bbbc5dd8c65a4ed9e> /System/Library/PrivateFrameworks/SharedWebCredentials.framework/SharedWebCredentials
0x1b090a000 - 0x1b0adbfff SafariServices arm64e  <65aab54dca1d3770b81664abd8d4eaf2> /System/Library/Frameworks/SafariServices.framework/SafariServices
0x1b0b30000 - 0x1b0b66fff DataAccessExpress arm64e  <2fe553f2569f3aadb2574eb22b052f6f> /System/Library/PrivateFrameworks/DataAccessExpress.framework/DataAccessExpress
0x1b0b67000 - 0x1b0b9efff CoreServicesStore arm64e  <a29a4d20ea023da887749802d406c6f0> /System/Library/PrivateFrameworks/CoreServicesStore.framework/CoreServicesStore
0x1b0b9f000 - 0x1b0bd1fff CoreAnalytics arm64e  <290dd79078a43fcbbd5ac2778add7668> /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics
0x1b0bd2000 - 0x1b0bddfff SymptomAnalytics arm64e  <51ddb6b718c532699c2ed2e5ed0d11bb> /System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomAnalytics.framework/SymptomAnalytics
0x1b0dd7000 - 0x1b0de6fff NanoPreferencesSync arm64e  <7074d8a49c253059ada91ef5f86f3497> /System/Library/PrivateFrameworks/NanoPreferencesSync.framework/NanoPreferencesSync
0x1b12e6000 - 0x1b1310fff IconServices arm64e  <378f46101b1c3f13b251dc4df5841a14> /System/Library/PrivateFrameworks/IconServices.framework/IconServices
0x1b1db6000 - 0x1b2073fff vImage arm64e  <6799ed9196bf3251a0141971e1dba349> /System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/vImage
0x1b2e86000 - 0x1b304dfff IMCore arm64e  <2e82ecb0d857330ea601ced19e48e839> /System/Library/PrivateFrameworks/IMCore.framework/IMCore
0x1b3142000 - 0x1b3159fff IAP arm64e  <2ec43d03daf43f3eba9310d23f3a1ca9> /System/Library/PrivateFrameworks/IAP.framework/IAP
0x1b315a000 - 0x1b31b5fff ktrace arm64e  <c96fd9da326b378fb54e1548186bec27> /System/Library/PrivateFrameworks/ktrace.framework/ktrace
0x1b31b6000 - 0x1b31b8fff libAXSafeCategoryBundle.dylib arm64e  <774af4f4c64933b2ba3e58d26d516d26> /usr/lib/libAXSafeCategoryBundle.dylib
0x1b3320000 - 0x1b332efff Celestial arm64e  <21bbaba8385f3a2b9f4615d30cd2862b> /System/Library/PrivateFrameworks/Celestial.framework/Celestial
0x1b33d5000 - 0x1b341cfff Pegasus arm64e  <393c6a96c4cd3fd196d2e59c9501eee3> /System/Library/PrivateFrameworks/Pegasus.framework/Pegasus
0x1b341d000 - 0x1b3583fff WebKitLegacy arm64e  <97f742e3cd8d39ab92f538f2b0b728e2> /System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy
0x1b35f9000 - 0x1b3678fff ClassKit arm64e  <44a3d9efeef030c9989d43835323ad55> /System/Library/Frameworks/ClassKit.framework/ClassKit
0x1b47fa000 - 0x1b4804fff IOMobileFramebuffer arm64e  <edcb4e03ae0f3a6daa18e7b58cfe7e71> /System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/IOMobileFramebuffer
0x1b4805000 - 0x1b4879fff ScreenTimeCore arm64e  <909c24460c4f3a57b5a0dd514f6fbc6d> /System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore
0x1b4925000 - 0x1b4aa7fff CloudPhotoLibrary arm64e  <d09fdf8cf9e731f0a45a32241c8d3db6> /System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/CloudPhotoLibrary
0x1b4aa8000 - 0x1b4d71fff MusicLibrary arm64e  <d8c56b414e1b30e3aed19e785880ae33> /System/Library/PrivateFrameworks/MusicLibrary.framework/MusicLibrary
0x1b4d72000 - 0x1b4ddafff CallKit arm64e  <1bc43750473f3d9b85e1ae3e16cdf345> /System/Library/Frameworks/CallKit.framework/CallKit
0x1b4e15000 - 0x1b4e7dfff AXRuntime arm64e  <ea391a8432c837d8a309fd40d0a97bbf> /System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime
0x1b4e7e000 - 0x1b4e9dfff PrototypeTools arm64e  <5d4a6b8ce90f3e01be29b4412f5d93ad> /System/Library/PrivateFrameworks/PrototypeTools.framework/PrototypeTools
0x1b4e9e000 - 0x1b4ec9fff PersistentConnection arm64e  <cf7e44035d383aa49fbcdd4a07dbe734> /System/Library/PrivateFrameworks/PersistentConnection.framework/PersistentConnection
0x1b4eca000 - 0x1b4f0cfff BiomeStreams arm64e  <542bab9ac7d239848edb9ee7f7f85bbb> /System/Library/PrivateFrameworks/BiomeStreams.framework/BiomeStreams
0x1b4f27000 - 0x1b51d5fff PencilKit arm64e  <e77d48daa45e3787b0e7fc6fca7ea61b> /System/Library/Frameworks/PencilKit.framework/PencilKit
0x1b5294000 - 0x1b5403fff CoreSpeech arm64e  <227ba80aad7831d590bb9d95b68d6587> /System/Library/PrivateFrameworks/CoreSpeech.framework/CoreSpeech
0x1b5404000 - 0x1b555afff IMDPersistence arm64e  <85494066690737db991a7ecf4cb330e7> /System/Library/PrivateFrameworks/IMDPersistence.framework/IMDPersistence
0x1b57f9000 - 0x1b58befff SafariSharedUI arm64e  <a197712142703d059112999cfd65f07b> /System/Library/PrivateFrameworks/SafariSharedUI.framework/SafariSharedUI
0x1b58bf000 - 0x1b58dafff TextToSpeech arm64e  <392def0df9b132d3bdaeb619c78cfc94> /System/Library/PrivateFrameworks/TextToSpeech.framework/TextToSpeech
0x1b58db000 - 0x1b58f1fff AppSSOCore arm64e  <bee1dcc591aa3f9988bea2e94679fd7c> /System/Library/PrivateFrameworks/AppSSOCore.framework/AppSSOCore
0x1b58fd000 - 0x1b5913fff CoreFollowUp arm64e  <cc5e87af00fa37b09a6d380e04d3ba80> /System/Library/PrivateFrameworks/CoreFollowUp.framework/CoreFollowUp
0x1b5914000 - 0x1b598cfff Rapport arm64e  <405d7688440d3aa2924bb1f86244d4e6> /System/Library/PrivateFrameworks/Rapport.framework/Rapport
0x1b5a6f000 - 0x1b5a80fff Categories arm64e  <96230226a6653a76b4c301f3c1ed9590> /System/Library/PrivateFrameworks/Categories.framework/Categories
0x1b5d4d000 - 0x1b5d74fff LocationSupport arm64e  <a9122a64832832828c0cdb82281c54ab> /System/Library/PrivateFrameworks/LocationSupport.framework/LocationSupport
0x1b5d75000 - 0x1b5da8fff iCalendar arm64e  <1fd2d9eeb1ed3eb6ae605cff8bbf86a8> /System/Library/PrivateFrameworks/iCalendar.framework/iCalendar
0x1b5da9000 - 0x1b5dd7fff CoreAccessories arm64e  <e1aaa56802da381585bf5d1de29d8f0e> /System/Library/PrivateFrameworks/CoreAccessories.framework/CoreAccessories
0x1b5dd8000 - 0x1b5ed6fff ConfigurationEngineModel arm64e  <440e0fb5a663328a87f43d3a157df4a2> /System/Library/PrivateFrameworks/ConfigurationEngineModel.framework/ConfigurationEngineModel
0x1b5ed7000 - 0x1b5f01fff CacheDelete arm64e  <c1b26eca70f6345bb30879796d6bb6e6> /System/Library/PrivateFrameworks/CacheDelete.framework/CacheDelete
0x1b5f02000 - 0x1b5f7cfff CVNLP arm64e  <f94d40fa3f363718ab7c2f7b535dd109> /System/Library/PrivateFrameworks/CVNLP.framework/CVNLP
0x1b60ec000 - 0x1b60eefff OSAServicesClient arm64e  <66fd299c9c13363d9689fd692ec0060b> /System/Library/PrivateFrameworks/OSAServicesClient.framework/OSAServicesClient
0x1b60ef000 - 0x1b60f1fff BiomeFoundation arm64e  <8b9bfd1bd2773eda81c14289cb256947> /System/Library/PrivateFrameworks/BiomeFoundation.framework/BiomeFoundation
0x1b60f2000 - 0x1b614bfff ProtectedCloudStorage arm64e  <46b99c91862a369f9fb82fc7c764a278> /System/Library/PrivateFrameworks/ProtectedCloudStorage.framework/ProtectedCloudStorage
0x1b614c000 - 0x1b6181fff C2 arm64e  <ed88f204bb963f3aa263fb0a89e203da> /System/Library/PrivateFrameworks/C2.framework/C2
0x1b6182000 - 0x1b63f4fff DifferentialPrivacy arm64e  <87b31fa143ca300cbfa65f8d44251ea8> /System/Library/PrivateFrameworks/DifferentialPrivacy.framework/DifferentialPrivacy
0x1b6627000 - 0x1b6e8cfff EmbeddedAcousticRecognition arm64e  <05849ddd81fa3c4298950d9d60931c40> /System/Library/PrivateFrameworks/EmbeddedAcousticRecognition.framework/EmbeddedAcousticRecognition
0x1b6e8d000 - 0x1b6f4bfff SiriInstrumentation arm64e  <29c63bbe7c24318dbae51d1c7cba1b40> /System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation
0x1b6f4c000 - 0x1b6f8ffff BiometricKit arm64e  <e95d0f6febdf3448936cf29d68e3963e> /System/Library/PrivateFrameworks/BiometricKit.framework/BiometricKit
0x1b6fe8000 - 0x1b7096fff CoreSymbolication arm64e  <8a670a45ec15393c8bb84b204ca6e71a> /System/Library/PrivateFrameworks/CoreSymbolication.framework/CoreSymbolication
0x1b710f000 - 0x1b71a0fff SpeakerRecognition arm64e  <b34b0533cdb133d8837c55549fd32b28> /System/Library/PrivateFrameworks/SpeakerRecognition.framework/SpeakerRecognition
0x1b785e000 - 0x1b7870fff IOSurface arm64e  <ed043e2a2ca03d6ba15f611435fec07a> /System/Library/Frameworks/IOSurface.framework/IOSurface
0x1b7871000 - 0x1b78d4fff MobileWiFi arm64e  <26b74509bf933221b8d2113ca8a9e5d3> /System/Library/PrivateFrameworks/MobileWiFi.framework/MobileWiFi
0x1b7db1000 - 0x1b7e59fff MMCS arm64e  <4d043effb2073077a8e043e3934cb246> /System/Library/PrivateFrameworks/MMCS.framework/MMCS
0x1b7eae000 - 0x1b7ee9fff libGLImage.dylib arm64e  <75d6f0925c9c3fbc8e33022d41c0cb5f> /System/Library/Frameworks/OpenGLES.framework/libGLImage.dylib
0x1b7eea000 - 0x1b7ef1fff libsystem_symptoms.dylib arm64e  <a9479247f833302e87f2bd85fa8a5d43> /usr/lib/system/libsystem_symptoms.dylib
0x1b7f3e000 - 0x1b8495fff CoreAudio arm64e  <d4dec3e7753a33b4b33ffa5a25730632> /System/Library/Frameworks/CoreAudio.framework/CoreAudio
0x1b8496000 - 0x1b84adfff ContactsDonation arm64e  <ffc935efb7b038679d6efdb28f80900d> /System/Library/PrivateFrameworks/ContactsDonation.framework/ContactsDonation
0x1b84ae000 - 0x1b84cbfff IntentsCore arm64e  <9028d5c697c43d8bb0fecd4dcff42256> /System/Library/PrivateFrameworks/IntentsCore.framework/IntentsCore
0x1b8570000 - 0x1b85a6fff ImageCaptureCore arm64e  <2b8365a3fb693670872d34a88c162c72> /System/Library/Frameworks/ImageCaptureCore.framework/ImageCaptureCore
0x1b8715000 - 0x1b885bfff Navigation arm64e  <0e30c2f34920330390d435b6ace6e644> /System/Library/PrivateFrameworks/Navigation.framework/Navigation
0x1b885c000 - 0x1b8878fff SafariFoundation arm64e  <890985d3fa293e60a9e1aef5d9cfbc18> /System/Library/PrivateFrameworks/SafariFoundation.framework/SafariFoundation
0x1b8a02000 - 0x1b8a15fff MaterialKit arm64e  <4fbb7876d49f3376a5f9b9c4fa8f6dba> /System/Library/PrivateFrameworks/MaterialKit.framework/MaterialKit
0x1b8bc0000 - 0x1b8bd0fff CoreAUC arm64e  <e3b46892fad13c269c96195ea06affb6> /System/Library/PrivateFrameworks/CoreAUC.framework/CoreAUC
0x1b942e000 - 0x1b9444fff SettingsFoundation arm64e  <f188d022cc5c33ca9c7b7b9100aa93b6> /System/Library/PrivateFrameworks/SettingsFoundation.framework/SettingsFoundation
0x1b9b8a000 - 0x1b9da5fff RawCamera arm64e  <9f898a6748383eecb2f840dca46cf6d7> /System/Library/CoreServices/RawCamera.bundle/RawCamera
0x1b9e10000 - 0x1b9e70fff ToneLibrary arm64e  <2c679a0610cb342bac1af68a0335c9d8> /System/Library/PrivateFrameworks/ToneLibrary.framework/ToneLibrary
0x1b9e71000 - 0x1b9edbfff TrialProto arm64e  <b9cac674e32031e6bc51545adc5f6168> /System/Library/PrivateFrameworks/TrialProto.framework/TrialProto
0x1ba6af000 - 0x1ba6bcfff MediaSafetyNet arm64e  <e98a7286a88f3580a6367a549d8402df> /System/Library/PrivateFrameworks/MediaSafetyNet.framework/MediaSafetyNet
0x1ba6bd000 - 0x1ba6f8fff TimeSync arm64e  <6d44855046b0382cac738a3056c82e7a> /System/Library/PrivateFrameworks/TimeSync.framework/TimeSync
0x1ba751000 - 0x1ba797fff ExposureNotification arm64e  <c80be0c1ee5a3b3795fd815b8fc2bd36> /System/Library/Frameworks/ExposureNotification.framework/ExposureNotification
0x1bae27000 - 0x1bae30fff CoreTime arm64e  <0a6ffb6c3c2831e4a719bc5794efc4e3> /System/Library/PrivateFrameworks/CoreTime.framework/CoreTime
0x1bb5c1000 - 0x1bb7bdfff NeutrinoCore arm64e  <de721e37dae73d7d877b9739428bc87b> /System/Library/PrivateFrameworks/NeutrinoCore.framework/NeutrinoCore
0x1bb7cd000 - 0x1bb8cafff TextRecognition arm64e  <626918c64ff93adca388897d52285eb5> /System/Library/PrivateFrameworks/TextRecognition.framework/TextRecognition
0x1bb9e5000 - 0x1bb9eefff ContextKitExtraction arm64e  <8c0ee13aa137303285d28efb5fa473ea> /System/Library/PrivateFrameworks/ContextKitExtraction.framework/ContextKitExtraction
0x1bbac3000 - 0x1bbac5fff libswiftObjectiveC.dylib arm64e  <ee7a900ac9453e42aab544f433210818> /usr/lib/swift/libswiftObjectiveC.dylib
0x1bbac6000 - 0x1bbd15fff libmorphun.dylib arm64e  <055e399a17e93aa089df5bed5b73859b> /usr/lib/libmorphun.dylib
0x1bd088000 - 0x1bd0c1fff PhotosPlayer arm64e  <4af16b290f8a3856bdc4d923a601b4fd> /System/Library/PrivateFrameworks/PhotosPlayer.framework/PhotosPlayer
0x1bd106000 - 0x1bd189fff CoreDAV arm64e  <94a2fdf61e6e35d3999fdc3bc86e7d94> /System/Library/PrivateFrameworks/CoreDAV.framework/CoreDAV
0x1bd366000 - 0x1bd375fff MobileIcons arm64e  <b9055ae58d883bc2a7625f396abc2e19> /System/Library/PrivateFrameworks/MobileIcons.framework/MobileIcons
0x1bd747000 - 0x1bd81bfff ProofReader arm64e  <039da53fefdb3e63ae906772e133554f> /System/Library/PrivateFrameworks/ProofReader.framework/ProofReader
0x1bea3c000 - 0x1bea93fff AccessibilitySharedSupport arm64e  <ed0a91ad8b9e3fc0af93d2756600d95b> /System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/AccessibilitySharedSupport
0x1bea94000 - 0x1bea9efff MallocStackLogging arm64e  <b5b085648b4d3c0a897afe9d07f25473> /System/Library/PrivateFrameworks/MallocStackLogging.framework/MallocStackLogging
0x1becd7000 - 0x1bed22fff MetadataUtilities arm64e  <9b6f1b1a7ce0354695c1113bd1d0f59e> /System/Library/PrivateFrameworks/MetadataUtilities.framework/MetadataUtilities
0x1bf4c3000 - 0x1bf521fff CoreLocationProtobuf arm64e  <4d14d172c7983a5583a0606417a5e05c> /System/Library/PrivateFrameworks/CoreLocationProtobuf.framework/CoreLocationProtobuf
0x1bf73e000 - 0x1bf770fff Bom arm64e  <2d61373c16eb3ef7be92b6b349c1f939> /System/Library/PrivateFrameworks/Bom.framework/Bom
0x1bf7a4000 - 0x1bf7aafff PushKit arm64e  <99ced58b1d403ab586144ceaeefbbe06> /System/Library/Frameworks/PushKit.framework/PushKit
0x1bf7ab000 - 0x1bf814fff PhotosFormats arm64e  <27d8be97ce483932a8521bd787debb07> /System/Library/PrivateFrameworks/PhotosFormats.framework/PhotosFormats
0x1bf9a6000 - 0x1bfa36fff Quagga arm64e  <7c0f3c42be3234b89cba5938861cb724> /System/Library/PrivateFrameworks/Quagga.framework/Quagga
0x1bfa37000 - 0x1bfa3ffff StudyLog arm64e  <20cf8d6250b5322c9e3a23731beb9acb> /System/Library/PrivateFrameworks/StudyLog.framework/StudyLog
0x1c097b000 - 0x1c09bcfff NaturalLanguage arm64e  <d234a62dc66133d7a56756ca08da28de> /System/Library/Frameworks/NaturalLanguage.framework/NaturalLanguage
0x1c1476000 - 0x1c1495fff MediaStream arm64e  <1fd20c6ebde339f6b50259b2e18013d1> /System/Library/PrivateFrameworks/MediaStream.framework/MediaStream
0x1c1ca4000 - 0x1c1cb3fff libAXSpeechManager.dylib arm64e  <97b7f50022db3358b7acc766bcf00da5> /usr/lib/libAXSpeechManager.dylib
0x1c1ff1000 - 0x1c211efff InternalSwiftProtobuf arm64e  <b0145f25164334008d33529f39fc3f7b> /System/Library/PrivateFrameworks/InternalSwiftProtobuf.framework/InternalSwiftProtobuf
0x1c2265000 - 0x1c228efff MediaConversionService arm64e  <4e769c5923863604b5e6dd24bd75870b> /System/Library/PrivateFrameworks/MediaConversionService.framework/MediaConversionService
0x1c23e4000 - 0x1c2527fff CoreHandwriting arm64e  <5088cf8514173aa6be9a41003978706e> /System/Library/PrivateFrameworks/CoreHandwriting.framework/CoreHandwriting
0x1c2d2a000 - 0x1c2d35fff AppleIDAuthSupport arm64e  <65167f6b77d33cec8ac0a55d86fa5dbf> /System/Library/PrivateFrameworks/AppleIDAuthSupport.framework/AppleIDAuthSupport
0x1c2d45000 - 0x1c2d5cfff LocalAuthentication arm64e  <b4aaa425ea053d09951ed0beb9f616f8> /System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication
0x1c2d5d000 - 0x1c2d63fff IOAccelerator arm64e  <1fee0ccb8dc134c4874b48614d266baa> /System/Library/PrivateFrameworks/IOAccelerator.framework/IOAccelerator
0x1c314e000 - 0x1c3158fff CloudPhotoServices arm64e  <c72c06d6aca23133a759dd44f829b50e> /System/Library/PrivateFrameworks/CloudPhotoServices.framework/CloudPhotoServices
0x1c31a0000 - 0x1c324bfff iTunesStore arm64e  <4c2aae64b1ed337893bc48b36976a233> /System/Library/PrivateFrameworks/iTunesStore.framework/iTunesStore
0x1c361e000 - 0x1c3650fff libsystem_kernel.dylib arm64e  <9dc3e02b8b833b9e8f0bc40df9d22680> /usr/lib/system/libsystem_kernel.dylib
0x1c395c000 - 0x1c3a66fff ResponseKit arm64e  <1259546ef1403e3593533e6f0dc0c7db> /System/Library/PrivateFrameworks/ResponseKit.framework/ResponseKit
0x1c3a67000 - 0x1c3aa1fff EmojiFoundation arm64e  <d16165d99c4e38f1b4bd21777e6b1fcd> /System/Library/PrivateFrameworks/EmojiFoundation.framework/EmojiFoundation
0x1c40d5000 - 0x1c40e2fff FontServices arm64e  <a128a3099d6b32e6a51ac5099f5c339a> /System/Library/PrivateFrameworks/FontServices.framework/FontServices
0x1c429c000 - 0x1c42a8fff MediaAccessibility arm64e  <6b16b3a5eaf634aeb2f369184f65064c> /System/Library/Frameworks/MediaAccessibility.framework/MediaAccessibility
0x1c42e9000 - 0x1c48c5fff SiriTTS arm64e  <b58adac5b80235e49dd10086ab3ece8d> /System/Library/PrivateFrameworks/SiriTTS.framework/SiriTTS
0x1c48c6000 - 0x1c48d4fff SetupAssistantSupport arm64e  <830df8000273318298b5eeba23a034ac> /System/Library/PrivateFrameworks/SetupAssistantSupport.framework/SetupAssistantSupport
0x1c48dd000 - 0x1c493dfff Social arm64e  <d9849b1147983d5ea9e41b1b5fedb62d> /System/Library/Frameworks/Social.framework/Social
0x1c4a1b000 - 0x1c4a4cfff VirtualGarage arm64e  <ae24a2d3de4031e492185663ccf06c82> /System/Library/PrivateFrameworks/VirtualGarage.framework/VirtualGarage
0x1c4a4d000 - 0x1c4a72fff NetAppsUtilities arm64e  <1980156aa29b36f4a9a3a5b20a823ff7> /System/Library/PrivateFrameworks/NetAppsUtilities.framework/NetAppsUtilities
0x1c4a73000 - 0x1c4ad4fff Osprey arm64e  <5729dece03c63f708f4c86d2289b69e4> /System/Library/PrivateFrameworks/Osprey.framework/Osprey
0x1c5c91000 - 0x1c5c9efff libdscsym.dylib arm64e  <01dafc30aa733d80992f59d2c75ff9b0> /usr/lib/libdscsym.dylib
0x1c5c9f000 - 0x1c5caffff HangTracer arm64e  <ebed1bd9c91b3f459cbc1591241a038b> /System/Library/PrivateFrameworks/HangTracer.framework/HangTracer
0x1c5e6b000 - 0x1c5f26fff SampleAnalysis arm64e  <9f10d38248e93a029fe1bb58e3e252fe> /System/Library/PrivateFrameworks/SampleAnalysis.framework/SampleAnalysis
0x1c5f27000 - 0x1c5f56fff PlugInKit arm64e  <4af494fc2c723d59adf96fdc6d88d34c> /System/Library/PrivateFrameworks/PlugInKit.framework/PlugInKit
0x1c600b000 - 0x1c600cfff libSystem.B.dylib arm64e  <c27b3faae299385db3c6ba1f501cf6bd> /usr/lib/libSystem.B.dylib
0x1c631d000 - 0x1c632afff MobileActivation arm64e  <351e42fb95b33694b8595a11ce19952d> /System/Library/PrivateFrameworks/MobileActivation.framework/MobileActivation
0x1c632b000 - 0x1c6383fff CalendarDaemon arm64e  <86f6af44150c3fca9d6eff7fc63d8db6> /System/Library/PrivateFrameworks/CalendarDaemon.framework/CalendarDaemon
0x1c6478000 - 0x1c64e8fff libarchive.2.dylib arm64e  <a5f1797225b6384f8fe5145b4cfd8ef5> /usr/lib/libarchive.2.dylib
0x1c64e9000 - 0x1c650dfff libtailspin.dylib arm64e  <9ad13a78f8b83d8f91d7d3ab8b502390> /usr/lib/libtailspin.dylib
0x1c650e000 - 0x1c69cbfff libBNNS.dylib arm64e  <52a56e95ecdc350c9d572acc81a90bed> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBNNS.dylib
0x1c69cc000 - 0x1c6a0ffff SharedUtils arm64e  <1cb3eede0cb63ade9e840a07217085ed> /System/Library/Frameworks/LocalAuthentication.framework/Support/SharedUtils.framework/SharedUtils
0x1c6cc3000 - 0x1c6cc8fff libsysdiagnose.dylib arm64e  <9173b7efc8083d17a3bc42c581754d9b> /usr/lib/libsysdiagnose.dylib
0x1c6d05000 - 0x1c6e10fff CoreMediaStream arm64e  <b79984a1ac043c2091db6f8252aaca7b> /System/Library/PrivateFrameworks/CoreMediaStream.framework/CoreMediaStream
0x1c7022000 - 0x1c7022fff AVFoundation arm64e  <7ea1a5e303743712982ec8c9f6306ae8> /System/Library/Frameworks/AVFoundation.framework/AVFoundation
0x1c7023000 - 0x1c7023fff Accelerate arm64e  <9f74aaf3dd663f9985b0bb20c848b4c3> /System/Library/Frameworks/Accelerate.framework/Accelerate
0x1c7024000 - 0x1c728efff libBLAS.dylib arm64e  <0f76c34314b33b7c8f1542a36f08a16e> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBLAS.dylib
0x1c728f000 - 0x1c774bfff libLAPACK.dylib arm64e  <09b4a3ecaf563afeaa3f5f168009f1e8> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libLAPACK.dylib
0x1c774c000 - 0x1c7760fff libLinearAlgebra.dylib arm64e  <5170f4bbc7c932d7aa80a77a2593b7ee> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libLinearAlgebra.dylib
0x1c7761000 - 0x1c7765fff libQuadrature.dylib arm64e  <ef8ef255765f3564b98b1550e20b6233> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libQuadrature.dylib
0x1c7766000 - 0x1c77c8fff libSparse.dylib arm64e  <dc1ce5b2943237809a6e8c2f9b632be3> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libSparse.dylib
0x1c77c9000 - 0x1c77dbfff libSparseBLAS.dylib arm64e  <69ad615846aa3531ad991f24295c0ff6> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libSparseBLAS.dylib
0x1c77dc000 - 0x1c782ffff libvMisc.dylib arm64e  <778cf0cc4eba3efc877c1c9b63acdbd9> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libvMisc.dylib
0x1c7830000 - 0x1c7830fff vecLib arm64e  <fcb5a1b2c7f43003a69fc7dbdeb77f03> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/vecLib
0x1c7837000 - 0x1c785efff AddressBook arm64e  <3d7cfcf57f323417bc77357296aa66de> /System/Library/Frameworks/AddressBook.framework/AddressBook
0x1c785f000 - 0x1c7865fff AddressBookUI arm64e  <e0de5280a4e7366db5e9a3e79429101c> /System/Library/Frameworks/AddressBookUI.framework/AddressBookUI
0x1c7868000 - 0x1c786bfff AppTrackingTransparency arm64e  <d9b53d3cf2843122b763eab6e8aa1e72> /System/Library/Frameworks/AppTrackingTransparency.framework/AppTrackingTransparency
0x1c786c000 - 0x1c787dfff AssetsLibrary arm64e  <b0dc0a9ad6aa3a1285d10a7073d9cf6d> /System/Library/Frameworks/AssetsLibrary.framework/AssetsLibrary
0x1c7993000 - 0x1c79b0fff AuthenticationServices arm64e  <4c3dd0c0bd5a3938b2e50f9d5145c6a3> /System/Library/Frameworks/AuthenticationServices.framework/AuthenticationServices
0x1c7a9f000 - 0x1c7b08fff CoreMIDI arm64e  <1be5b59010153bcdb36b0e07786215ba> /System/Library/Frameworks/CoreMIDI.framework/CoreMIDI
0x1c8034000 - 0x1c804bfff ExternalAccessory arm64e  <3adfec7c6934369e900d6f259043abef> /System/Library/Frameworks/ExternalAccessory.framework/ExternalAccessory
0x1c805f000 - 0x1c8085fff GLKit arm64e  <e2eff97fdd1d33a7ae0a8d2163f68a1d> /System/Library/Frameworks/GLKit.framework/GLKit
0x1c8086000 - 0x1c80b3fff GSS arm64e  <eec24dfdf3683c67ad58a81885ff6bcc> /System/Library/Frameworks/GSS.framework/GSS
0x1c822d000 - 0x1c83b1fff MLCompute arm64e  <5c33e40cc3123117ac5ca03809678a48> /System/Library/Frameworks/MLCompute.framework/MLCompute
0x1c83d8000 - 0x1c83f0fff MetalKit arm64e  <64afc30392113945b7bba4645fe3256f> /System/Library/Frameworks/MetalKit.framework/MetalKit
0x1c83f1000 - 0x1c8477fff MPSImage arm64e  <e840623d60e93126b1707d1ee80f6b9b> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSImage.framework/MPSImage
0x1c8478000 - 0x1c849efff MPSMatrix arm64e  <9ed118a2df1f365f8ad86ac3755bb2e2> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSMatrix.framework/MPSMatrix
0x1c849f000 - 0x1c84d9fff MPSNDArray arm64e  <3d598a46571c3de990c3eb91ac364bb0> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNDArray.framework/MPSNDArray
0x1c84da000 - 0x1c8522fff MPSRayIntersector arm64e  <ed66e72903243683bc4c6d020cfbe132> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSRayIntersector.framework/MPSRayIntersector
0x1c8523000 - 0x1c8523fff MetalPerformanceShaders arm64e  <1237ca52c0cb3a9f8eb9092b223a80f4> /System/Library/Frameworks/MetalPerformanceShaders.framework/MetalPerformanceShaders
0x1c88c0000 - 0x1c88c0fff MobileCoreServices arm64e  <f91ed54e4a8f3180b311ead827257e9a> /System/Library/Frameworks/MobileCoreServices.framework/MobileCoreServices
0x1c94a8000 - 0x1c94b0fff OpenGLES arm64e  <110bd129653b365281f8218e50eef407> /System/Library/Frameworks/OpenGLES.framework/OpenGLES
0x1c94b1000 - 0x1c94b2fff libCVMSPluginSupport.dylib arm64e  <5f67f6e0c22f39d2a55f47bdfb533b11> /System/Library/Frameworks/OpenGLES.framework/libCVMSPluginSupport.dylib
0x1c94b3000 - 0x1c94b9fff libCoreFSCache.dylib arm64e  <3e00e01aeb2630e7973751700390f5cd> /System/Library/Frameworks/OpenGLES.framework/libCoreFSCache.dylib
0x1c94ba000 - 0x1c94bffff libCoreVMClient.dylib arm64e  <918fdadf04683ad8a7b696cf30f64d53> /System/Library/Frameworks/OpenGLES.framework/libCoreVMClient.dylib
0x1c94c0000 - 0x1c94c9fff libGFXShared.dylib arm64e  <c80c5f7c6877308db9c48bec7f305d6f> /System/Library/Frameworks/OpenGLES.framework/libGFXShared.dylib
0x1c9682000 - 0x1c9748fff PDFKit arm64e  <fe295dbc992d3f058d117c48bb5867c0> /System/Library/Frameworks/PDFKit.framework/PDFKit
0x1c9757000 - 0x1c9792fff QuickLookThumbnailing arm64e  <85cfa32371733c73817afdeb17687dde> /System/Library/Frameworks/QuickLookThumbnailing.framework/QuickLookThumbnailing
0x1c9e64000 - 0x1c9fa8fff SoundAnalysis arm64e  <b901c8092e3933e58f65ab60efd65a99> /System/Library/Frameworks/SoundAnalysis.framework/SoundAnalysis
0x1c9fa9000 - 0x1c9fbafff Speech arm64e  <6b90dd254954346fa67d43155cd8ceb2> /System/Library/Frameworks/Speech.framework/Speech
0x1ca0d7000 - 0x1ca0d7fff UIKit arm64e  <9548e1f9335e369385444eda26b7dbeb> /System/Library/Frameworks/UIKit.framework/UIKit
0x1ca0e1000 - 0x1ca1aafff VideoSubscriberAccount arm64e  <ec1ec265b10f36a9ac8f49074012586d> /System/Library/Frameworks/VideoSubscriberAccount.framework/VideoSubscriberAccount
0x1ca1ab000 - 0x1cad95fff libfaceCore.dylib arm64e  <9f71b99591ef32e88c69c3fc7cf83f76> /System/Library/Frameworks/Vision.framework/libfaceCore.dylib
0x1cb288000 - 0x1cb28bfff AFKUser arm64e  <e564c8f1a96f30a88af6cbd957fe1219> /System/Library/PrivateFrameworks/AFKUser.framework/AFKUser
0x1cb350000 - 0x1cb5d6fff ANECompiler arm64e  <b0ba1cc822883d7d9bc450afd20c3e6a> /System/Library/PrivateFrameworks/ANECompiler.framework/ANECompiler
0x1cb5d7000 - 0x1cb5ebfff ANEServices arm64e  <d6d78422f6193e4ba89eb0e56065a92b> /System/Library/PrivateFrameworks/ANEServices.framework/ANEServices
0x1cb5f0000 - 0x1cb6affff APFS arm64e  <015e5415d2993c39bf30335174e07b1c> /System/Library/PrivateFrameworks/APFS.framework/APFS
0x1cb6b0000 - 0x1cb6b6fff ASEProcessing arm64e  <41e01d6e59953ae6911ce3b9254154f2> /System/Library/PrivateFrameworks/ASEProcessing.framework/ASEProcessing
0x1cbed7000 - 0x1cbedcfff AggregateDictionary arm64e  <6429bf54f842383f87d73b4f0c4666d8> /System/Library/PrivateFrameworks/AggregateDictionary.framework/AggregateDictionary
0x1cc071000 - 0x1cc147fff AirPlaySync arm64e  <c9ededfcbcff3af0821c68389339a151> /System/Library/PrivateFrameworks/AirPlaySync.framework/AirPlaySync
0x1cc250000 - 0x1cc26cfff AlgosScoreFramework arm64e  <99028404ec3c31e0bcbe3de71a7309fb> /System/Library/PrivateFrameworks/AlgosScoreFramework.framework/AlgosScoreFramework
0x1cc396000 - 0x1cc51ffff AppC3D arm64e  <9c8446c45afc3cb68adaad29f6c40a1e> /System/Library/PrivateFrameworks/AppC3D.framework/AppC3D
0x1cc520000 - 0x1cc542fff AppConduit arm64e  <b9b852301ed1332ca7c96a4cda28ec4e> /System/Library/PrivateFrameworks/AppConduit.framework/AppConduit
0x1cd788000 - 0x1cd929fff AppleCVA arm64e  <2cc74d14b3373446a58fdff0cedb8931> /System/Library/PrivateFrameworks/AppleCVA.framework/AppleCVA
0x1cd97a000 - 0x1cd989fff AppleFSCompression arm64e  <10f7ff6b4fa035c49e41f6f76c660542> /System/Library/PrivateFrameworks/AppleFSCompression.framework/AppleFSCompression
0x1cd997000 - 0x1cd9bbfff AppleIDSSOAuthentication arm64e  <0b78da2c62033e1e858d65beaaa023f7> /System/Library/PrivateFrameworks/AppleIDSSOAuthentication.framework/AppleIDSSOAuthentication
0x1cd9bc000 - 0x1cda01fff AppleJPEG arm64e  <ae8b9a0c6075355baa29813bf5110130> /System/Library/PrivateFrameworks/AppleJPEG.framework/AppleJPEG
0x1cdaa1000 - 0x1cdab4fff AppleNeuralEngine arm64e  <a11c3f99651e3f13a75a291e1dc8572c> /System/Library/PrivateFrameworks/AppleNeuralEngine.framework/AppleNeuralEngine
0x1cdabe000 - 0x1cdae2fff AppleSauce arm64e  <dbb0b2a0655b37afb2968036bdf48c21> /System/Library/PrivateFrameworks/AppleSauce.framework/AppleSauce
0x1cdb15000 - 0x1cdb33fff AssetCacheServices arm64e  <41277159e11c372eac39c93b7516ea9a> /System/Library/PrivateFrameworks/AssetCacheServices.framework/AssetCacheServices
0x1cdc9a000 - 0x1cdcf7fff AuthKitUI arm64e  <2a6af7331dcf368cb928cec95df5481b> /System/Library/PrivateFrameworks/AuthKitUI.framework/AuthKitUI
0x1cdcf8000 - 0x1cdd4bfff AutoLoop arm64e  <0f0f502aa3fa3c5c9139e3a836b1a7f5> /System/Library/PrivateFrameworks/AutoLoop.framework/AutoLoop
0x1cdd84000 - 0x1cdd9dfff BiomePubSub arm64e  <56d0175c37db3e12816237edc1e63c75> /System/Library/PrivateFrameworks/BiomePubSub.framework/BiomePubSub
0x1ce09e000 - 0x1ce0adfff BluetoothManager arm64e  <6e75aaf194a532c0807e1256d2842cf5> /System/Library/PrivateFrameworks/BluetoothManager.framework/BluetoothManager
0x1ce323000 - 0x1ce32dfff CMCaptureCore arm64e  <2442683ea568390688d8041ff32b0837> /System/Library/PrivateFrameworks/CMCaptureCore.framework/CMCaptureCore
0x1ce32e000 - 0x1ce344fff CPAnalytics arm64e  <e26fc647198332b0bebeccb1c0f1b223> /System/Library/PrivateFrameworks/CPAnalytics.framework/CPAnalytics
0x1ce347000 - 0x1ce356fff CPMS arm64e  <999b3fe797a5374c86511e578c562852> /System/Library/PrivateFrameworks/CPMS.framework/CPMS
0x1ce357000 - 0x1ce366fff CTCarrierSpace arm64e  <bae68e7904543f80b50842415a155855> /System/Library/PrivateFrameworks/CTCarrierSpace.framework/CTCarrierSpace
0x1ce4d1000 - 0x1ce4fbfff CameraEditKit arm64e  <be1acb8042fe3d9788772cd6d0e677c7> /System/Library/PrivateFrameworks/CameraEditKit.framework/CameraEditKit
0x1ce66b000 - 0x1ce676fff CaptiveNetwork arm64e  <6f914041dbc83fe6a78ddad84c4d1b49> /System/Library/PrivateFrameworks/CaptiveNetwork.framework/CaptiveNetwork
0x1ce795000 - 0x1ce7e2fff Catalyst arm64e  <a18c9f5334f931dca294ef1f760268a7> /System/Library/PrivateFrameworks/Catalyst.framework/Catalyst
0x1ce7e3000 - 0x1ce807fff CellularPlanManager arm64e  <50b9ede5b72b39f09cc13fa11621f8a5> /System/Library/PrivateFrameworks/CellularPlanManager.framework/CellularPlanManager
0x1ce81f000 - 0x1ce827fff CertUI arm64e  <c0987479713b3312a5528ab5182ff4fd> /System/Library/PrivateFrameworks/CertUI.framework/CertUI
0x1ce830000 - 0x1ce87ffff ChunkingLibrary arm64e  <b9b16f9f83d130b6af25e869a5e939bc> /System/Library/PrivateFrameworks/ChunkingLibrary.framework/ChunkingLibrary
0x1cece1000 - 0x1cece8fff CommonAuth arm64e  <40718cb7309736c09047325a3dfc370f> /System/Library/PrivateFrameworks/CommonAuth.framework/CommonAuth
0x1cece9000 - 0x1cecedfff CommunicationsFilter arm64e  <5c72b548ab2c3a02b7b4f38f58922ad6> /System/Library/PrivateFrameworks/CommunicationsFilter.framework/CommunicationsFilter
0x1ceda3000 - 0x1ceda6fff ConstantClasses arm64e  <5d690ef5cc7738f9a02930dd2488360c> /System/Library/PrivateFrameworks/ConstantClasses.framework/ConstantClasses
0x1cedb0000 - 0x1cedeefff ContactsAutocomplete arm64e  <6228c3f83424324d81d03a076ff6b1fe> /System/Library/PrivateFrameworks/ContactsAutocomplete.framework/ContactsAutocomplete
0x1cedf4000 - 0x1cee6cfff ContactsUICore arm64e  <64ceee6d9e043140bf74f8e36e7841a5> /System/Library/PrivateFrameworks/ContactsUICore.framework/ContactsUICore
0x1ceea9000 - 0x1cef02fff CoreAppleCVA arm64e  <a24828e495f031738558410d3aae5c5a> /System/Library/PrivateFrameworks/CoreAppleCVA.framework/CoreAppleCVA
0x1cef03000 - 0x1ceffefff CoreBrightness arm64e  <efdb6c37a6173dada07becda8d67dfdc> /System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness
0x1cf06a000 - 0x1cf077fff CoreDuetDaemonProtocol arm64e  <987cbd2eb84f3813beaf122ff1a42bac> /System/Library/PrivateFrameworks/CoreDuetDaemonProtocol.framework/CoreDuetDaemonProtocol
0x1cf07a000 - 0x1cf07cfff CoreDuetDebugLogging arm64e  <07e4965c43113fe78a8f20f1e257d8b1> /System/Library/PrivateFrameworks/CoreDuetDebugLogging.framework/CoreDuetDebugLogging
0x1cf08b000 - 0x1cf09dfff CoreEmoji arm64e  <f91b221cc30138cf85eaf1df5d93b903> /System/Library/PrivateFrameworks/CoreEmoji.framework/CoreEmoji
0x1cf6c5000 - 0x1cf6c9fff CoreOptimization arm64e  <375f1501244632e49cbf5b860d478f00> /System/Library/PrivateFrameworks/CoreOptimization.framework/CoreOptimization
0x1cf6ca000 - 0x1cf786fff CorePDF arm64e  <446d8518b301379686148748a5e495b2> /System/Library/PrivateFrameworks/CorePDF.framework/CorePDF
0x1cf787000 - 0x1cf78ffff CorePhoneNumbers arm64e  <c22483c7030633399389e0e81112ec3f> /System/Library/PrivateFrameworks/CorePhoneNumbers.framework/CorePhoneNumbers
0x1cf790000 - 0x1cf7e7fff CorePrediction arm64e  <e45b639f47713c3c9b13818c013b7087> /System/Library/PrivateFrameworks/CorePrediction.framework/CorePrediction
0x1d0114000 - 0x1d011ffff CoreRecents arm64e  <ba904177b0cb3964ae40bfbe850a0f36> /System/Library/PrivateFrameworks/CoreRecents.framework/CoreRecents
0x1d0120000 - 0x1d0187fff CoreRecognition arm64e  <db50c8ef26c43971ad11ce3171fb2a2c> /System/Library/PrivateFrameworks/CoreRecognition.framework/CoreRecognition
0x1d0188000 - 0x1d019efff CoreSDB arm64e  <8920057f68323d4eb29b56c88ae1ade1> /System/Library/PrivateFrameworks/CoreSDB.framework/CoreSDB
0x1d019f000 - 0x1d01c9fff CoreSVG arm64e  <9ce70e262d903607846de8d3652b53a3> /System/Library/PrivateFrameworks/CoreSVG.framework/CoreSVG
0x1d03e0000 - 0x1d03e4fff DAAPKit arm64e  <ae893eeb90ac3fd7951b360bbd55f1e7> /System/Library/PrivateFrameworks/DAAPKit.framework/DAAPKit
0x1d0405000 - 0x1d0412fff DCIMServices arm64e  <62f8ad8df8e53397b1800dbe13f0bc1a> /System/Library/PrivateFrameworks/DCIMServices.framework/DCIMServices
0x1d0429000 - 0x1d0465fff DataDetectorsNaturalLanguage arm64e  <f3edf8e458413658a1e7d8a4321d2d77> /System/Library/PrivateFrameworks/DataDetectorsNaturalLanguage.framework/DataDetectorsNaturalLanguage
0x1d04c3000 - 0x1d04f8fff DeviceIdentity arm64e  <48927908910a3144b0a10ccfda8f3a86> /System/Library/PrivateFrameworks/DeviceIdentity.framework/DeviceIdentity
0x1d0628000 - 0x1d065ffff DistributedEvaluation arm64e  <7c3c018657203dd2a5cea335efa3b1df> /System/Library/PrivateFrameworks/DistributedEvaluation.framework/DistributedEvaluation
0x1d077f000 - 0x1d07b9fff DocumentManager arm64e  <512d1af14ace37c7b828b15f99f4c3eb> /System/Library/PrivateFrameworks/DocumentManager.framework/DocumentManager
0x1d07ba000 - 0x1d07d8fff DocumentManagerCore arm64e  <636fe26321573c5aafc87ae548ea5efc> /System/Library/PrivateFrameworks/DocumentManagerCore.framework/DocumentManagerCore
0x1d085f000 - 0x1d0861fff DragUI arm64e  <5cadb3a3dc1134dc9a279439befee747> /System/Library/PrivateFrameworks/DragUI.framework/DragUI
0x1d0892000 - 0x1d08c3fff EAP8021X arm64e  <c11a9420b0043505bde300b5b3acec40> /System/Library/PrivateFrameworks/EAP8021X.framework/EAP8021X
0x1d08f3000 - 0x1d0908fff Engram arm64e  <36a7bd63f77031cc956d3aa39ec099d3> /System/Library/PrivateFrameworks/Engram.framework/Engram
0x1d0a41000 - 0x1d0a47fff ExtensionFoundation arm64e  <d7ef192e25b03e2795698e5023669a24> /System/Library/PrivateFrameworks/ExtensionFoundation.framework/ExtensionFoundation
0x1d0bd7000 - 0x1d0be3fff FSEvents arm64e  <99c7b07af30137af8b5dc4112df1932e> /System/Library/PrivateFrameworks/FSEvents.framework/FSEvents
0x1d0be4000 - 0x1d0c03fff FTAWD arm64e  <edd28e9f0afd3a03a952d785cd1d01f6> /System/Library/PrivateFrameworks/FTAWD.framework/FTAWD
0x1d0c04000 - 0x1d0c07fff FTClientServices arm64e  <1c8acdc5981338c6bc4aa02c3b0044dd> /System/Library/PrivateFrameworks/FTClientServices.framework/FTClientServices
0x1d0c08000 - 0x1d101bfff FaceCore arm64e  <c0b0cecb5de5371eade5aded8f48cca8> /System/Library/PrivateFrameworks/FaceCore.framework/FaceCore
0x1d1022000 - 0x1d1027fff FeatureFlagsSupport arm64e  <2b28836c473f3be9b5694a32ebfd912c> /System/Library/PrivateFrameworks/FeatureFlagsSupport.framework/FeatureFlagsSupport
0x1d1028000 - 0x1d1033fff FeedbackLogger arm64e  <1ad709e5d38a3505a9031d263d07bc76> /System/Library/PrivateFrameworks/FeedbackLogger.framework/FeedbackLogger
0x1d11c9000 - 0x1d130bfff libFontParser.dylib arm64e  <f54d59ac57933249839792d85d31fa84> /System/Library/PrivateFrameworks/FontServices.framework/libFontParser.dylib
0x1d130c000 - 0x1d1314fff libGSFont.dylib arm64e  <4d4074ce23cd3317859fca4e364ba6e7> /System/Library/PrivateFrameworks/FontServices.framework/libGSFont.dylib
0x1d1315000 - 0x1d1352fff libGSFontCache.dylib arm64e  <5c5b8aec25c63dd69ddc91ec347e0e27> /System/Library/PrivateFrameworks/FontServices.framework/libGSFontCache.dylib
0x1d13b8000 - 0x1d13c5fff libhvf.dylib arm64e  <02e28642439036c5b5d0092aa0ef7a1e> /System/Library/PrivateFrameworks/FontServices.framework/libhvf.dylib
0x1d13ed000 - 0x1d1404fff Futhark arm64e  <d83493f136f334c2803acea23a25d43d> /System/Library/PrivateFrameworks/Futhark.framework/Futhark
0x1d2078000 - 0x1d2096fff GenerationalStorage arm64e  <7a0c46fb74793cd3a4d27b028420ce14> /System/Library/PrivateFrameworks/GenerationalStorage.framework/GenerationalStorage
0x1d2097000 - 0x1d20a4fff GraphVisualizer arm64e  <e07a065e5c3f39b38a98944c195c96da> /System/Library/PrivateFrameworks/GraphVisualizer.framework/GraphVisualizer
0x1d20d2000 - 0x1d20defff HID arm64e  <d444d6bb57663576b31c6d91193dd225> /System/Library/PrivateFrameworks/HID.framework/HID
0x1d228b000 - 0x1d22fdfff Heimdal arm64e  <b4834a8fd50a3a2682ca36e830c697b5> /System/Library/PrivateFrameworks/Heimdal.framework/Heimdal
0x1d26f2000 - 0x1d2766fff HomeSharing arm64e  <25d243b4b3f832da8d2db04605b9612d> /System/Library/PrivateFrameworks/HomeSharing.framework/HomeSharing
0x1d27c0000 - 0x1d27c6fff IDSKVStore arm64e  <9bee446557c83870a1aece7b211bb24d> /System/Library/PrivateFrameworks/IDSKVStore.framework/IDSKVStore
0x1d2abf000 - 0x1d2adbfff IOGPU arm64e  <61f639bf45e631ebb838b4f6844881d8> /System/Library/PrivateFrameworks/IOGPU.framework/IOGPU
0x1d2add000 - 0x1d2ae6fff IOKitten arm64e  <75f9eb18acba3faf930004df726d6a3d> /System/Library/PrivateFrameworks/IOKitten.framework/IOKitten
0x1d2ae7000 - 0x1d2ae9fff IOSurfaceAccelerator arm64e  <218acab8117f31a18854d295e6963527> /System/Library/PrivateFrameworks/IOSurfaceAccelerator.framework/IOSurfaceAccelerator
0x1d2b11000 - 0x1d2b18fff IdleTimerServices arm64e  <666a2892b47339dfa691e06c60b99f50> /System/Library/PrivateFrameworks/IdleTimerServices.framework/IdleTimerServices
0x1d2b21000 - 0x1d2b27fff IncomingCallFilter arm64e  <1c804deebdd638ea94b42382c7246a6f> /System/Library/PrivateFrameworks/IncomingCallFilter.framework/IncomingCallFilter
0x1d2b28000 - 0x1d2ba4fff InertiaCam arm64e  <ba574c99eff538efbe9a98323a82c357> /System/Library/PrivateFrameworks/InertiaCam.framework/InertiaCam
0x1d2be8000 - 0x1d2bf5fff IntentsFoundation arm64e  <4ae64cc7970437e6bb87ae50f93de0c4> /System/Library/PrivateFrameworks/IntentsFoundation.framework/IntentsFoundation
0x1d2c0f000 - 0x1d2c11fff InternationalTextSearch arm64e  <63620d98a7383ab489026512bcf8d12c> /System/Library/PrivateFrameworks/InternationalTextSearch.framework/InternationalTextSearch
0x1d2c12000 - 0x1d2c2efff IntlPreferences arm64e  <b28e2cd73be6317893eef1f47efc888c> /System/Library/PrivateFrameworks/IntlPreferences.framework/IntlPreferences
0x1d2e94000 - 0x1d2e9afff LinguisticData arm64e  <8dff5cad25133da1bfbed98c958cc97d> /System/Library/PrivateFrameworks/LinguisticData.framework/LinguisticData
0x1d2eea000 - 0x1d2f22fff LocalAuthenticationPrivateUI arm64e  <25041360835136c8a54199b801ab9907> /System/Library/PrivateFrameworks/LocalAuthenticationPrivateUI.framework/LocalAuthenticationPrivateUI
0x1d30eb000 - 0x1d30ebfff Marco arm64e  <ffb9057ffcac3413b02295ff8f0c8596> /System/Library/PrivateFrameworks/Marco.framework/Marco
0x1d33fc000 - 0x1d36c2fff MediaLibraryCore arm64e  <5adc3bc2d91a375db8371637950bca77> /System/Library/PrivateFrameworks/MediaLibraryCore.framework/MediaLibraryCore
0x1d36c3000 - 0x1d3715fff MediaPlatform arm64e  <e1bd0f78b03a3798b05fde4c864b429a> /System/Library/PrivateFrameworks/MediaPlatform.framework/MediaPlatform
0x1d3b06000 - 0x1d3bd8fff MetalTools arm64e  <3bd33294ec583803b088b2ff66530f39> /System/Library/PrivateFrameworks/MetalTools.framework/MetalTools
0x1d3bfa000 - 0x1d3c56fff MetricsKit arm64e  <54896ccac801352a8d5f0e8f36beaf68> /System/Library/PrivateFrameworks/MetricsKit.framework/MetricsKit
0x1d3c67000 - 0x1d3ca0fff MobileBluetooth arm64e  <a2754151eccb383bbab2d8e57f5372e1> /System/Library/PrivateFrameworks/MobileBluetooth.framework/MobileBluetooth
0x1d3d21000 - 0x1d3d27fff MobileSystemServices arm64e  <c840119f1cb13378b7bb8bc2878487e9> /System/Library/PrivateFrameworks/MobileSystemServices.framework/MobileSystemServices
0x1d3e03000 - 0x1d3e09fff Netrb arm64e  <db3b29a317d930e58826f9720159dc56> /System/Library/PrivateFrameworks/Netrb.framework/Netrb
0x1d3ede000 - 0x1d3efcfff NeutrinoKit arm64e  <b660fc56b21a3e029ec2102234506b14> /System/Library/PrivateFrameworks/NeutrinoKit.framework/NeutrinoKit
0x1d3f3a000 - 0x1d3f3cfff OAuth arm64e  <afa17a5cf7e33fac8910b3cfe538eb8d> /System/Library/PrivateFrameworks/OAuth.framework/OAuth
0x1d3f5a000 - 0x1d3f99fff OTSVG arm64e  <10aedfae8f2d3c538555db11c9f7d4b1> /System/Library/PrivateFrameworks/OTSVG.framework/OTSVG
0x1d45d1000 - 0x1d45d3fff ParsecSubscriptionServiceSupport arm64e  <0cae424363fb30b2bd2fccd5bef8e417> /System/Library/PrivateFrameworks/ParsecSubscriptionServiceSupport.framework/ParsecSubscriptionServiceSupport
0x1d45d8000 - 0x1d4602fff Pasteboard arm64e  <51d4e52518303785bc847b6de7ebc17c> /System/Library/PrivateFrameworks/Pasteboard.framework/Pasteboard
0x1d4632000 - 0x1d463cfff PersonaKit arm64e  <cbd72173f8193e17b857d78f6993c909> /System/Library/PrivateFrameworks/PersonaKit.framework/PersonaKit
0x1d463d000 - 0x1d4649fff PersonaUI arm64e  <b09b8c866bc933fda6b9b50369a0cefd> /System/Library/PrivateFrameworks/PersonaUI.framework/PersonaUI
0x1d4683000 - 0x1d4683fff PhoneNumbers arm64e  <acd113c985ce351ba38d325f3b412c1e> /System/Library/PrivateFrameworks/PhoneNumbers.framework/PhoneNumbers
0x1d468c000 - 0x1d47a3fff PhotoImaging arm64e  <421d614b663f3e839098d13aee2d581f> /System/Library/PrivateFrameworks/PhotoImaging.framework/PhotoImaging
0x1d47a4000 - 0x1d4801fff PhotoLibrary arm64e  <b8a1ee62ccaf3796afd1aedf70b37451> /System/Library/PrivateFrameworks/PhotoLibrary.framework/PhotoLibrary
0x1d484a000 - 0x1d4889fff PhotosImagingFoundation arm64e  <04b268590cee38879d7f7e2f2f93e143> /System/Library/PrivateFrameworks/PhotosImagingFoundation.framework/PhotosImagingFoundation
0x1d488a000 - 0x1d48d4fff PhysicsKit arm64e  <8d7ac40cbb083fc1a06980035d4a341c> /System/Library/PrivateFrameworks/PhysicsKit.framework/PhysicsKit
0x1d497f000 - 0x1d498afff PointerUIServices arm64e  <d4b955b568d83136abde5de90b7e18ef> /System/Library/PrivateFrameworks/PointerUIServices.framework/PointerUIServices
0x1d5dd6000 - 0x1d5de3fff PrototypeToolsUI arm64e  <76ab03c1841739ea88c54dcab33eaa39> /System/Library/PrivateFrameworks/PrototypeToolsUI.framework/PrototypeToolsUI
0x1d5e61000 - 0x1d5e6cfff RTCReporting arm64e  <f21395cd55f736feb604358e62160ae6> /System/Library/PrivateFrameworks/RTCReporting.framework/RTCReporting
0x1d60fc000 - 0x1d610cfff RemoteTextInput arm64e  <7fdec7042c3f33ec8bc40bd58168517d> /System/Library/PrivateFrameworks/RemoteTextInput.framework/RemoteTextInput
0x1d610d000 - 0x1d6174fff RemoteUI arm64e  <df39da1fd49f3079a426449653250c41> /System/Library/PrivateFrameworks/RemoteUI.framework/RemoteUI
0x1d61a3000 - 0x1d61a7fff RevealCore arm64e  <a1c374eb8d9133fba1778c7e1b3864a3> /System/Library/PrivateFrameworks/RevealCore.framework/RevealCore
0x1d61be000 - 0x1d6545fff SDAPI arm64e  <2f68346b178033f48da6189897ed242e> /System/Library/PrivateFrameworks/SDAPI.framework/SDAPI
0x1d7c9d000 - 0x1d7ca7fff SignpostCollection arm64e  <c934fb3542623d3ba0e27b8d4d0008c9> /System/Library/PrivateFrameworks/SignpostCollection.framework/SignpostCollection
0x1d7ca8000 - 0x1d7ca8fff SignpostMetrics arm64e  <510052bc2b173ba5b7786cef28dad85e> /System/Library/PrivateFrameworks/SignpostMetrics.framework/SignpostMetrics
0x1d7caa000 - 0x1d7ce7fff SignpostSupport arm64e  <cf7e5270ac953d0795606d6a58bcdae4> /System/Library/PrivateFrameworks/SignpostSupport.framework/SignpostSupport
0x1d88dc000 - 0x1d88dcfff SoftLinking arm64e  <09787ff7596f3c30b996dafe6efc77ca> /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking
0x1d8ccc000 - 0x1d8d0afff StreamingZip arm64e  <4a4ce8e8f12c36fcb99eca0130513b3d> /System/Library/PrivateFrameworks/StreamingZip.framework/StreamingZip
0x1d8d12000 - 0x1d8d1cfff SymptomDiagnosticReporter arm64e  <719efb62e171351492daac70fef4bb0c> /System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter
0x1d8d4d000 - 0x1d8d69fff SymptomPresentationFeed arm64e  <eba06df06b193c80af89a136572e9a66> /System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomPresentationFeed.framework/SymptomPresentationFeed
0x1d8da6000 - 0x1d8db6fff TCC arm64e  <32a914201ec83acd99b8838c4a7fc80b> /System/Library/PrivateFrameworks/TCC.framework/TCC
0x1d9676000 - 0x1d9729fff TextureIO arm64e  <3d381bb7222030d28ed5af45a6ad72e9> /System/Library/PrivateFrameworks/TextureIO.framework/TextureIO
0x1d9951000 - 0x1d9958fff URLFormatting arm64e  <e14301a0b2493e0ba048a04e1919ec8e> /System/Library/PrivateFrameworks/URLFormatting.framework/URLFormatting
0x1d9f3c000 - 0x1d9f65fff UsageTracking arm64e  <dd0d27b85566343fb6193c7423f4f1ac> /System/Library/PrivateFrameworks/UsageTracking.framework/UsageTracking
0x1daa91000 - 0x1dab5afff VoiceTrigger arm64e  <01bd6ec5b9b63764a8a500302f721acb> /System/Library/PrivateFrameworks/VoiceTrigger.framework/VoiceTrigger
0x1dac29000 - 0x1dac2afff WatchdogClient arm64e  <c2ac1adb1a3c369db3aa7d7c9bd3b9d3> /System/Library/PrivateFrameworks/WatchdogClient.framework/WatchdogClient
0x1daf94000 - 0x1db6d4fff libwebrtc.dylib arm64e  <dcc13f91e5613aefad4670f7358aa090> /System/Library/PrivateFrameworks/WebCore.framework/Frameworks/libwebrtc.dylib
0x1db753000 - 0x1db768fff WebUI arm64e  <ab3a89eed4983047b969ecb92ed67da1> /System/Library/PrivateFrameworks/WebUI.framework/WebUI
0x1dbc8d000 - 0x1dbc90fff XCTTargetBootstrap arm64e  <de8929352cf13ba293104dd80b7d41c5> /System/Library/PrivateFrameworks/XCTTargetBootstrap.framework/XCTTargetBootstrap
0x1dbd2b000 - 0x1dbd4afff caulk arm64e  <4ec06f67b8d3360fb8b58f5a904ebc17> /System/Library/PrivateFrameworks/caulk.framework/caulk
0x1de322000 - 0x1de327fff kperf arm64e  <0bdabb8da6d83bb1b4fe278afab6d35f> /System/Library/PrivateFrameworks/kperf.framework/kperf
0x1de328000 - 0x1de330fff kperfdata arm64e  <31a790c4352936e0b1d050e9bc64b2bd> /System/Library/PrivateFrameworks/kperfdata.framework/kperfdata
0x1de331000 - 0x1de347fff libEDR arm64e  <5fd819d2546b3c39be1f9f6432122458> /System/Library/PrivateFrameworks/libEDR.framework/libEDR
0x1de360000 - 0x1de370fff perfdata arm64e  <57b7888103013f9381f1f19974d1a9fb> /System/Library/PrivateFrameworks/perfdata.framework/perfdata
0x1de371000 - 0x1de3a0fff vCard arm64e  <a922cc4455c132b5bd490a068c827cf0> /System/Library/PrivateFrameworks/vCard.framework/vCard
0x1dec04000 - 0x1dec43fff libAWDSupport.dylib arm64e  <f2018a479dba34b3ad900708574ca51d> /usr/lib/libAWDSupport.dylib
0x1dec44000 - 0x1defe4fff libAWDSupportFramework.dylib arm64e  <627181793a5a36489e5ceffd6ff6a954> /usr/lib/libAWDSupportFramework.dylib
0x1df174000 - 0x1df183fff libAudioStatistics.dylib arm64e  <9dab6db632a3364399428812c8bd94ac> /usr/lib/libAudioStatistics.dylib
0x1df327000 - 0x1df359fff libCRFSuite.dylib arm64e  <56755c30e50c3756870f46ade976897a> /usr/lib/libCRFSuite.dylib
0x1df35a000 - 0x1df35bfff libCTGreenTeaLogger.dylib arm64e  <6fe82a00fab3304e9e76891f00b9354c> /usr/lib/libCTGreenTeaLogger.dylib
0x1df35c000 - 0x1df366fff libChineseTokenizer.dylib arm64e  <1a93b9d124a332f2b5e807cd1de469c7> /usr/lib/libChineseTokenizer.dylib
0x1df5fd000 - 0x1df604fff libIOReport.dylib arm64e  <b776ffbe44723ac0bcd6352e4450b4be> /usr/lib/libIOReport.dylib
0x1df680000 - 0x1df687fff libMatch.1.dylib arm64e  <16848f014db336549ff27c5b034bd6a7> /usr/lib/libMatch.1.dylib
0x1df7a3000 - 0x1df7a4fff libThaiTokenizer.dylib arm64e  <c853e3cc8165397490ef20ce97948d3d> /usr/lib/libThaiTokenizer.dylib
0x1dfa10000 - 0x1dfa12fff libapp_launch_measurement.dylib arm64e  <4ebf359bb7a7325d98004f1b99d6fa12> /usr/lib/libapp_launch_measurement.dylib
0x1dfa13000 - 0x1dfa29fff libapple_nghttp2.dylib arm64e  <605659a5d877341ba3737336615a3095> /usr/lib/libapple_nghttp2.dylib
0x1dfa2a000 - 0x1dfabbfff libate.dylib arm64e  <7c350d30683a3274a3e280b697f5d528> /usr/lib/libate.dylib
0x1dfb4c000 - 0x1dfb5cfff libbsm.0.dylib arm64e  <2af1ba56570b39c5bd69874bff995a6f> /usr/lib/libbsm.0.dylib
0x1dfb5d000 - 0x1dfb69fff libbz2.1.0.dylib arm64e  <b28dd143bd053e97a3c0e6dc919eae57> /usr/lib/libbz2.1.0.dylib
0x1dfb6a000 - 0x1dfb6afff libcharset.1.dylib arm64e  <0b03cd28416133ea8ce3ac944caa74e6> /usr/lib/libcharset.1.dylib
0x1dfb6b000 - 0x1dfb7cfff libcmph.dylib arm64e  <97cda63f8d8c37068b2ed84129933dec> /usr/lib/libcmph.dylib
0x1dfb7d000 - 0x1dfb9bfff libcompression.dylib arm64e  <2d1fa073d8053a9eaace04564b4860d6> /usr/lib/libcompression.dylib
0x1dfb9c000 - 0x1dfbb2fff libcoretls.dylib arm64e  <da2bd2f7f05239a18c55ba0117c59d3b> /usr/lib/libcoretls.dylib
0x1dfbb3000 - 0x1dfbb4fff libcoretls_cfhelpers.dylib arm64e  <76494581d8ec336b956d14cef03e0b22> /usr/lib/libcoretls_cfhelpers.dylib
0x1dfbda000 - 0x1dfbe1fff libcupolicy.dylib arm64e  <c438197bf51a3fbbbce3778a97c85504> /usr/lib/libcupolicy.dylib
0x1dfbe2000 - 0x1dfbe9fff libdns_services.dylib arm64e  <f923a2901b263f27988a5feda73b4d2c> /usr/lib/libdns_services.dylib
0x1dfbea000 - 0x1dfc07fff libedit.3.dylib arm64e  <ada87d800b26371e883c0af2dce745a4> /usr/lib/libedit.3.dylib
0x1dfc08000 - 0x1dfc0cfff libenergytrace.dylib arm64e  <52966a15a91e3ba2aea8d98c81f48f8b> /usr/lib/libenergytrace.dylib
0x1dfc0d000 - 0x1dfc26fff libexpat.1.dylib arm64e  <f8d9d056a5b63c369abbdb413a60599e> /usr/lib/libexpat.1.dylib
0x1dfc53000 - 0x1dfc57fff libgermantok.dylib arm64e  <c31706503b133f4d92a524a468a64ca8> /usr/lib/libgermantok.dylib
0x1dfc58000 - 0x1dfc5dfff libheimdal-asn1.dylib arm64e  <31806f0c003235c8840319628da8e60a> /usr/lib/libheimdal-asn1.dylib
0x1dfc5e000 - 0x1dfd4ffff libiconv.2.dylib arm64e  <79d4893880f2381f93704b13a93b1350> /usr/lib/libiconv.2.dylib
0x1dfd6e000 - 0x1dfd6ffff liblangid.dylib arm64e  <441bdfc8b4443e1a8fef429cd2335f9e> /usr/lib/liblangid.dylib
0x1dfd70000 - 0x1dfd7bfff liblockdown.dylib arm64e  <a01eca8337d63d62be2df5236e7fd73f> /usr/lib/liblockdown.dylib
0x1dfd7c000 - 0x1dfd94fff liblzma.5.dylib arm64e  <010b201489573da5aa8c7b0852439cd1> /usr/lib/liblzma.5.dylib
0x1dfdc3000 - 0x1dfe19fff libmecab.dylib arm64e  <c83cdbb8c94136c39bb23d76a07cb527> /usr/lib/libmecab.dylib
0x1dfe1a000 - 0x1e0054fff libmecabra.dylib arm64e  <31462453bc993ee28d99826e7beb8d58> /usr/lib/libmecabra.dylib
0x1e0055000 - 0x1e0068fff libmis.dylib arm64e  <a49cec87b4f03575859ae8b47c1c6a49> /usr/lib/libmis.dylib
0x1e0069000 - 0x1e007ffff libnetworkextension.dylib arm64e  <fbda03ac83433ef08d671eadf0d9e5c6> /usr/lib/libnetworkextension.dylib
0x1e042a000 - 0x1e0465fff libpcap.A.dylib arm64e  <c78cf9d4972b3e2bbe897aeb9b59b9ee> /usr/lib/libpcap.A.dylib
0x1e0466000 - 0x1e0473fff libperfcheck.dylib arm64e  <0e64680484a73167a22081723780a8fb> /usr/lib/libperfcheck.dylib
0x1e047b000 - 0x1e048dfff libprequelite.dylib arm64e  <6ed383b0be3c393397331cf1e48574ab> /usr/lib/libprequelite.dylib
0x1e048e000 - 0x1e04a0fff libprotobuf-lite.dylib arm64e  <afab139aa55d35ae986e665d6a633011> /usr/lib/libprotobuf-lite.dylib
0x1e04a1000 - 0x1e0502fff libprotobuf.dylib arm64e  <79d4b9b244443e5880aef02e70b035e7> /usr/lib/libprotobuf.dylib
0x1e0503000 - 0x1e05a0fff libquic.dylib arm64e  <4ecd8f0cdb0c33a09f9ac36d627c644b> /usr/lib/libquic.dylib
0x1e05a1000 - 0x1e05b9fff libresolv.9.dylib arm64e  <d27a840d65993fffbd1a3c606598880c> /usr/lib/libresolv.9.dylib
0x1e05ba000 - 0x1e05bcfff libsandbox.1.dylib arm64e  <3b9909f374d738c093563d81d64b0ddb> /usr/lib/libsandbox.1.dylib
0x1e0604000 - 0x1e0607fff libutil.dylib arm64e  <af241b79c7fe386495e4a6c2483eedfb> /usr/lib/libutil.dylib
0x1e0608000 - 0x1e06f4fff libxml2.2.dylib arm64e  <d36d6a565db130269e4b1d2fd2595a9c> /usr/lib/libxml2.2.dylib
0x1e06f9000 - 0x1e0722fff libxslt.1.dylib arm64e  <01e6a4db90db361f8ca5c2e4b177d462> /usr/lib/libxslt.1.dylib
0x1e0723000 - 0x1e0734fff libz.1.dylib arm64e  <cf6652657d9b3cf8910140a63357fa2c> /usr/lib/libz.1.dylib
0x1e082d000 - 0x1e082dfff libswiftCoreFoundation.dylib arm64e  <eadf2127a4223f91ad6268833eb2739e> /usr/lib/swift/libswiftCoreFoundation.dylib
0x1e088a000 - 0x1e0893fff libswiftDarwin.dylib arm64e  <a8fa8d5fc7043da1b3ebecd6fc2deb8b> /usr/lib/swift/libswiftDarwin.dylib
0x1e096e000 - 0x1e0980fff libswiftos.dylib arm64e  <8fc96a0c1402380684755c6400d8963e> /usr/lib/swift/libswiftos.dylib
0x1e0994000 - 0x1e0999fff libcache.dylib arm64e  <95ea8f419aee3b26af5bca27b579d251> /usr/lib/system/libcache.dylib
0x1e099a000 - 0x1e09a7fff libcommonCrypto.dylib arm64e  <f77673ca175733fa9b678e1fb0f9c511> /usr/lib/system/libcommonCrypto.dylib
0x1e09a8000 - 0x1e09abfff libcompiler_rt.dylib arm64e  <a9445d9ccac1329e9203cdcabb520ceb> /usr/lib/system/libcompiler_rt.dylib
0x1e09ac000 - 0x1e09b4fff libcopyfile.dylib arm64e  <44a492a51b4b360dabd9d47da13d2fc2> /usr/lib/system/libcopyfile.dylib
0x1e0a9a000 - 0x1e0a9afff liblaunch.dylib arm64e  <6eb4b289527b3335b602ac76700441cd> /usr/lib/system/liblaunch.dylib
0x1e0a9b000 - 0x1e0aa0fff libmacho.dylib arm64e  <57c258368ebd34859320269989903067> /usr/lib/system/libmacho.dylib
0x1e0aa1000 - 0x1e0aa3fff libremovefile.dylib arm64e  <521f4fd0d7ad3e68826315c49fa08494> /usr/lib/system/libremovefile.dylib
0x1e0aa4000 - 0x1e0aa5fff libsystem_blocks.dylib arm64e  <2df2fb0e3db835beb7a8e1ba370de403> /usr/lib/system/libsystem_blocks.dylib
0x1e0aa6000 - 0x1e0aa8fff libsystem_collections.dylib arm64e  <05802caeab98393e9a9f7480fa6bd917> /usr/lib/system/libsystem_collections.dylib
0x1e0aa9000 - 0x1e0aadfff libsystem_configuration.dylib arm64e  <cfd43ebc732e3fdfaa01d2a7b7287a22> /usr/lib/system/libsystem_configuration.dylib
0x1e0aae000 - 0x1e0ac0fff libsystem_containermanager.dylib arm64e  <8a1755b048c232a9ac923f1b5073c28c> /usr/lib/system/libsystem_containermanager.dylib
0x1e0ac1000 - 0x1e0ac2fff libsystem_coreservices.dylib arm64e  <e2c346d27aba304abbd57caf2f95dddb> /usr/lib/system/libsystem_coreservices.dylib
0x1e0ac3000 - 0x1e0accfff libsystem_darwin.dylib arm64e  <fc234bac09613db9afbc51c54b536fde> /usr/lib/system/libsystem_darwin.dylib
0x1e0acd000 - 0x1e0ad5fff libsystem_dnssd.dylib arm64e  <3bfcc2d108093297983dd97980f498b7> /usr/lib/system/libsystem_dnssd.dylib
0x1e0ad6000 - 0x1e0ad8fff libsystem_featureflags.dylib arm64e  <768215fa64da36cc88d0cd4477e78139> /usr/lib/system/libsystem_featureflags.dylib
0x1e0ad9000 - 0x1e0b06fff libsystem_m.dylib arm64e  <e0ceadffe5f63a36bb66b7032586a1d0> /usr/lib/system/libsystem_m.dylib
0x1e0b07000 - 0x1e0b0dfff libsystem_platform.dylib arm64e  <4f256518f4e435c7ba0e3f0c26b9d24e> /usr/lib/system/libsystem_platform.dylib
0x1e0b0e000 - 0x1e0b0efff libsystem_product_info_filter.dylib arm64e  <440f41e74dcb3ba69c8f899c9713cb7f> /usr/lib/system/libsystem_product_info_filter.dylib
0x1e0b0f000 - 0x1e0b1afff libsystem_pthread.dylib arm64e  <3690509ee1e03f8c8935688b599c0303> /usr/lib/system/libsystem_pthread.dylib
0x1e0b1b000 - 0x1e0b1efff libsystem_sandbox.dylib arm64e  <0b8928ee11603b00a6c3c50be6686457> /usr/lib/system/libsystem_sandbox.dylib
0x1e0b1f000 - 0x1e0b29fff libunwind.dylib arm64e  <3402ad4a2a0f3170b7ca8502818e1941> /usr/lib/system/libunwind.dylib
0x1e0b2a000 - 0x1e0b60fff libxpc.dylib arm64e  <b247010424003575a30a563c5d057b4a> /usr/lib/system/libxpc.dylib
0x1e0c04000 - 0x1e0c1efff AccessibilitySettingsLoader arm64e  <36b0dc5201de32b9856f732b93bf603a> /System/Library/AccessibilityBundles/AccessibilitySettingsLoader.bundle/AccessibilitySettingsLoader
0x1e122e000 - 0x1e1539fff AGXMetalA12 arm64e  <21e5749ca10d327f9d01615deee3751c> /System/Library/Extensions/AGXMetalA12.bundle/AGXMetalA12
0x1e153a000 - 0x1e1647fff AVFAudio arm64e  <fcbae8e28d70338f8125e48f82b0e9da> /System/Library/Frameworks/AVFAudio.framework/AVFAudio
0x1e18f5000 - 0x1e18fbfff AuthenticationServicesCore arm64e  <3d1f1fc8a3fb3d9999530c443e904035> /System/Library/PrivateFrameworks/AuthenticationServicesCore.framework/AuthenticationServicesCore
0x1e18fc000 - 0x1e1909fff CMImaging arm64e  <f073b228281b3227b3b8a7bf200b2469> /System/Library/PrivateFrameworks/CMImaging.framework/CMImaging
0x1e190a000 - 0x1e1920fff CinematicFraming arm64e  <39e294a38fc33bb29e445341bbecafdc> /System/Library/PrivateFrameworks/CinematicFraming.framework/CinematicFraming
0x1e1a11000 - 0x1e1a29fff CoreSpeechFoundation arm64e  <be120db782533d2dbac71c8d66018f2d> /System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/CoreSpeechFoundation
0x1e1bc0000 - 0x1e1bd0fff MobileSafari arm64e  <7247cfe24fa63b2588b49341cbea8f18> /System/Library/PrivateFrameworks/MobileSafari.framework/MobileSafari
0x1e1c3e000 - 0x1e24d4fff PegasusAPI arm64e  <a14a09c3ea46379f85c1fb8297cded7e> /System/Library/PrivateFrameworks/PegasusAPI.framework/PegasusAPI
0x1e2622000 - 0x1e2626fff SiriLiminal arm64e  <a775c3ce252c3105ba0db90ba583cd03> /System/Library/PrivateFrameworks/SiriLiminal.framework/SiriLiminal
0x1e27af000 - 0x1e27c1fff SpotlightLinguistics arm64e  <ef723adb57e234cd864a120ddaefb9c0> /System/Library/PrivateFrameworks/SpotlightLinguistics.framework/SpotlightLinguistics

EOF

