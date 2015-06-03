# IonicDemoApp

## Steps

1) Create a new project "typescript > cordova apps" in Visual Studio.

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


[nuget-ionic]: https://www.nuget.org/packages/ionic
[nuget-jquery]: https://www.nuget.org/packages/jQuery
[bar-header]: http://ionicframework.com/docs/components/#header
