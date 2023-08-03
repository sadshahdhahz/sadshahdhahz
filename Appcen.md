using Microsoft.AppCenter;
using Microsoft.AppCenter.LIXR;
using Microsoft.AppCenter.APP;

AppCenter.Start("{APP LIXR }",
                   typeof(LIXR), typeof(APP));

"8c868950-db39-4b59-89f8-3dc6b3732690"

{appSecret} ON TOP

using Microsoft.AppCenter;
using Microsoft.AppCenter.Analytics;
using Microsoft.AppCenter.Crashes;

AppCenter.Start("ios={LIXR APPS };" +
                  "uwp={UWP LIXR APP };" +
                  "android={IDK};" +
                  "macos={IDK};",
                  typeof(Analytics), typeof(Crashes))
