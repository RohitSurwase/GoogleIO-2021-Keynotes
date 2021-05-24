# Google I/O 2021 Keynotes
### List of each and every announcement from all Android sessions

**If you think anything needs to be added or removed, feel free to contribute.**

1. Un-deprecated @Deprecated which was deprecated by accident
2. Introduced Theme.DeviceDefault and Theme.DeviceDefault.DayNight
3. Added new color palettes to use within App
4. Improved Widgets - selection, configuration, placement
5. Widgets can use new devices themes
6. New Launch/Splash-Screen Animations by default for all Apps which can be customised further
7. Notifications - redesigned all templates, deprecated full custom remote views
8. Notifications - Trampoline - Notifications must start an Activity from contentIntent
9. Toast can show App icon, reduced text length
10. Capped number of toasts that any App can have/show in a given time
11. Picture-in-picture mode new API to animate transition
12. Blur Content can be used on any view, windowContent or other content
13. Ripple effect improved to Stacked Effect enabled by default
14. New Edge Effect - Replaced Glow with Stretch
15. New image format - AVIF - better quality, lesser size
16. Media type fallback
17. Audio-coupled Haptic Playback
18. Privacy - New separate permission for Bluetooth access - BLUETOOTH_SCAN, BLUETOOTH_CONNECT instead of broder Location permission
19. Introduced Approximate location so user can choose to share or not the exact location.
20. User will see a toast to know which App accessed the Clipboard, it will be ignored if content was copied by same app
21. Deferring foreground notification by 10sec so there will be less distraction to the user. App can override this behaviour
22. Not allowed to launch Foreground service from the background, it can be launched in response to user interaction only. But there are few more excemptions to launch it.
23. Introduced ‘Expedited Jobs’ with low latency and high reliability but maximum allocated duration will be shorter. Executes during Dose and Battery Saver. Subject to standby buckets so less used apps will have fewer opportunities to launch this job. Expedited Jobs also available through WorkManager v2.7
24. Foreground service should be used for only meaning full task for the user, like music player, navigation…
25. Work Manager is One Stop Solution recommended for all background tasks. Can schedule Expedited, Periodic and Opportunistic work
26. Collapsed similar feature - Drag & Drop, Copy & Paste, Keyboard Stickers
27. New library to Benchmark an App
28. Service charges reduced to 15% instead of 30% for first $1M (USD) of earnings
29. New Policy and program section on console
30. New SDK Console for SDK developers
31. App bundle is required for new apps
32. New engagement metrics and benchmark comparison with peer
33. New Payment methods
34. New Multi-quantity purchases
35. New Multi-line subscriptions
36. Prepaid plans
37. New Play Billing Library v4.0
38. Privacy : Microphone and camera indicators in status bar
39. New Privacy dashboard in Android Settings
40. Added Data Access auditing APIs > AppOpsManager
41. Introduced new options in the Notification Centre to turn of Camera and Mic access for all apps, these would no impact the App which are using permission best practices
42. Motion sensor sampling rate limited to 200 Hz
43. Made Guest mode switching easier
44. New runtime permission for Nearby 
45. App hibernation system
46. Restriction on MANAGE_EXTERNAL_STORAGE & QUERY_APP_PACKAGES permissions
47. Using Private Compute Core to deliver intelligence features without compromising privacy. Usage - Smart reply
48. Removed direct Network permission from Private Compute Core instead using open source APK - Private Compute Services
49. Well defined Foreground Service in https://www.youtube.com/watch?v=IqnCqHyu1E4
50. In Android 12, most sensitive components are re-written using a better language - Rust language
51. Android Ready SE (Secured Elements) - an advanced physical security
52. New Jetpack Security Suite
53. Introduced ability to hide overlay window apps
54. Added setAuthenticationRequired flag to Notification action builder
55. Added App Compatibility Changes > set of toggles to isolates testing for certain conditions under Developer Options
56. Further restricted access to network MAC address
57. android:exported = “true/false” attribute is compulsory to mention 
58. Improved App Links to reduce user friction
59. Changes in Webviews > Samesite cookies
60. Overscroll - more natural scroll stop indicator. Verify scrolling container compatibility for GridView, ListView, RecyclerView, ViewPager
61. Untrusted touch events
62. Exact Alarm permission
63. Widgets - added support for more interactive view components 
64. Widgets can be shown on more new places
65. Introduced System-level Resources for consistence widget on launcher home-screen
66. Smoother transition between widget and app can be achieved using ID
67. Support for Animated Vector Drawable in Design Tools
68. New Macrobenchmark library to measure Jank and Startup
69. New Security-Crypto library


