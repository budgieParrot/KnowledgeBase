# iOS Knowledge Matrix

:green_heart: - for knowledge and experience
</br>:yellow_heart: - for some knowledge and experience
<br/>:heart: - no knowledge and experience

## User Interface

Qualified | Competent | Expert
:--|:--|:--
*Autolayout* | |
:yellow_heart: Anatomy of constraint, <br/>external and internal changes, autolayout vs frame-based layout |  :heart: Stackview, debugging autolayout, anchors, safe area, self-sized views, <br/>Hugging priority/Content compression resistance" | :heart: Layout directions (left-to-right/right-to-left), <br/>VFL, <br/>autoresizing masks (springs&struts)
*Xibs (Nibs), Storyboards* | |
:green_heart: xibs and/vs storyboards, custom UI elements in xibs and storyboards, file's owner, loading from xibs and storyboards programmaticaly, segue, pass data via segue, customization ui best practices | :heart: IBInspectable, IBDesignable, size classes,  xib vs nib, NIB object lifecycle, unwind segues, git conflicts in xibs and storyboards, xib's xml structure |
*Animations* | |
:heart: animations via autolayout, UIView.animate, CALayer, CAAnimation | :heart: facebook pop, UIDynamics, 3D animations, UIViewPropertyAnimator, CADisplayLink | :heart: SpriteKit? Adobe After Effects?
*Other* | |
:green_heart: Localizations<br/>[HIG](https://developer.apple.com/ios/human-interface-guidelines/overview/) | :yellow_heart: Internationalization i18n & Localisation l10n |

## Data persistence

Qualified | Competent | Expert
:--|:--|:--
*Core Data* | |
:yellow_heart: Core Data Stack & Architecture, Relationships, Data Types, fetching | :heart: Pefrormance, concurrency, multithreading, multiple contexts, changes and updates tracking | :heart: Migrations, nestedcontexts, profiling, persistence under the hood (SQLite, XML, Binary, In-memory). iCloud synchronization,Security
*Other approaches* | |
:yellow_heart: UserDefaults, KeyedArchiver | :yellow_heart: Realm, Keychain |


## Languages

Qualified | Competent | Expert
:--|:--|:--
*Swift* | |
:yellow_heart: Basic syntax, optionals, control flow, error handling, memory management (ARC), classes, structures, enums, functions, initialization/deinitialization, inheritance | :yellow_heart: Objective-CInteroperability, POP, generics, type safety, KVO/KVC, value and reference types, subscripts, bitwise operators, overflow operators, operator methods, access control | :heart: Swift performance, Swift + LLVM, method dispatch, swizzling, @dynamic, final, playgrounds, Swift Standard Library
*Objective-C* | |
:yellow_heart: Basic syntax, variables and types, collections, initializations | :yellow_heart: Blocks, categories, Integrating Swift into objc, C/C++ code usage inside Obj-C | :heart: Runtime, Class structure (isa), Method swizzling, MRC


## Networking

Qualified | Competent | Expert
:--|:--|:--
*URLSession* | |
:green_heart: NSURLSession basics, encoding/decoding of URL data, lifecycle of a URL Session | :yellow_heart: Multipart requests, response caching, handling redirects | :heart: Background handling, NSURLAuthentication, TLS Chain Validation, streams, sockets, NSURLConnection
*Response handling* | |
:green_heart: JSONSerialization, error handling | :heart: Codable/Decodable, NSCoding |
*Building a network layer* | |
:heart: Alamofire, mappers | :heart: Moya , CFNetwork|


## Deployment

Qualified | Competent | Expert
:--|:--|:--
:green_heart: Understanding of code signing, provisioning profiles, app schemes configuration. Launching app on device | :yellow_heart: Working with iTunes Connect, App Review Guidelines. Build automation, beta-testing tools and deployment platforms. Fastlane | :heart: Advanced automation skills (plugins, scripts)

## iOS essentials

Qualified | Competent | Expert
:--|:--|:--
:green_heart: UIViewController lifecycle, iOS app lifecycle, NotificationCenter | :yellow_heart: Working with filesystem, background modes, xcode project structure |  |


## Multithreading

Qualified | Competent | Expert
:--|:--|:--
*Grand Central Dispatch* | |
:yellow_heart: basic knowledge about multithreading and concurrent programming, deadlocks, race conditions. async vs sync, main vs background |  :heart: Dispatch queues, units of work, prioritizing, quality of service, timing (time & after) | :heart: Dispatch groups, semaphores, dispatch I/O, dispatch sources. Interprocess communication, XPC Services |
*NSOperation* | |
:heart: basic knowledge about multithreading and concurrent programming, deadlocks, race conditions. |  :heart: Operation executing, cancelling and configuring. Operation states. NSOperationQueue. Subclassing and overriding. BlockOperation |:heart: Operation dependencies, NSOperationQueue |
*Thread (NSThread)* | |
| | :heart: Ability to work with Thread. Initializing, starting/stopping, state handling, prioritizing. Locks, NSRunLoop. |

## Marketing

Qualified | Competent | Expert
:--|:--|:--
:green_heart: Push Notifications, URL schemes |  :yellow_heart: Deep linking, Universal links, App Indexing | :heart: Advertisements (AdSupport, AdMob etc) |

## Testing

Qualified | Competent | Expert
:--|:--|:--
:green_heart: Basic knowledge of unit tests | :heart: Complex unit tests, XCTest, Quick/Nimble (Kiwi for Obj-C) | :heart: TDD, UI tests, web testing and debugging |

## Xcode build system

Qualified | Competent | Expert
:--|:--|:--
 |:yellow_heart: xcodebuild, xcrun. Targets, bundles, frameworks, libraries. pbxproj, xcconfig, xcodeproj, xcworkspace, xcscheme, xctoolchain. Build phases, shell scripts, build rules, build configurations. | :heart: lldb, lipo, llbuild, swift package manager, linker. Flags |

## Security

Qualified | Competent | Expert
:--|:--|:--
 | :yellow_heart: Keychain, iOS security guidelines, TouchID, FaceID | :heart: Security framework - authorization and authentication, code signing, cryptography, result codes. Secure coding guide. iOS security overview |

## Performance

Qualified | Competent | Expert
:--|:--|:--
:heart: Basic knowledge of measuring app performance with Xcode instruments. Object Graph, Network Link Conditioner. UI optimization (opaque views, fat XIBs, image sizes, main thread blockers, layers vs paths etc) | :heart: Optimization modes in Xcode, whole module optimization, gzip compression, lazy load and reuse of views, caching, tableview and collectionview optimization, date formatters |:heart: Memory warnings handling, speeding up app launch time (static vs dynamic libraries, merging several frameworks into one monolithic) |

## Architecture Patterns

Qualified | Competent | Expert
:--|:--|:--
:green_heart: Delegate, MVC, observer, chain of responsibility, Singleton. | :yellow_heart: MVP, MVVM, VIPER, VIP, Router. State, Strategy, Visitor. Abstract Factory, Factory Method, Builder. Adapter, Decorator, Facade. | :yellow_heart: Flux, Redux. Mediator, Memento, Command, Prototype, Proxy |

## Functional/Reactive programming

Qualified | Competent | Expert
:--|:--|:--
:yellow_heart: Basic knowledge. Recursion | :heart: RxSwift/ReactiveCocoa/ReactiveSwift/ReactiveKit, higher order functions. | :heart: Futures&Promises. Pure functions. Complete understanding of reactive approach. Functors, Applicatives and Monads. |

## Hardware & Media

Qualified | Competent | Expert
:--|:--|:--
:heart: Basic AVFoundation, CoreBluetooth, AVKit | :heart: Core Audio. Advanced AVFoundation, CoreBluetooth, AVKit. WebKit. Core Telephony, Core Media | :heart: Core Motion, IOKit, Compression |

## Other

Qualified | Competent | Expert
:--|:--|:--
:yellow_heart: Basic MapKit & CoreLocation. Basic socials integration. Sharing | :heart: AddressBook, AddressBookUI, Messages, MessagesUI, Advanced MapKit & CoreLocation. Advanced socials integration. | :heart: In-app purchases |

## Optionals

Qualified | Competent | Expert
:--|:--|:--
:heart: App extensions | :heart: tvOS, watchOS, SpriteKit, SceneKit, HomeKit, HealthKit, EventKit | :heart: Metal, CoreGraphics, OpenGL, cross-platform development, ARKit CryptoTokenKit, SiriKit |
