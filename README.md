# IonicDemoApp

## Installation

1) Install [Git for Windows][win-git].

2) Install [Console][win-console] if you want too. You may need it for Ionic.

3) Install [Visual Studio Tools][win-cordova] for Apache Cordova.

4) Reboot Windows.

5) Run Visual Studio.

## Developement

1) Create a new project "TypeScript > Cordova apps" in Visual Studio.

2) Get [Ionic][nuget-ionic] and [JQuery][nuget-jquery] from nuget.

3) With others scripts add :
```html
<script src="scripts/jquery-2.1.3.js"></script>
<script src="scripts/ionic.bundle.js"></script>
```

4) With others styles add :
```html
<link href="Content/ionic.css" rel="stylesheet" />
```

5) Add a simple ionic component like a [bar-header][bar-header] :
```html
<div class="bar bar-header bar-balanced">
  <h1 class="title">bar-balanced</h1>
</div>
```

6) Run your projet

[win-git]: http://git-scm.com/download/win
[win-console]: http://sourceforge.net/projects/console/
[win-cordova]: https://www.visualstudio.com/en-us/cordova-vs.aspx
[nuget-ionic]: https://www.nuget.org/packages/ionic
[nuget-jquery]: https://www.nuget.org/packages/jQuery
[bar-header]: http://ionicframework.com/docs/components/#header
