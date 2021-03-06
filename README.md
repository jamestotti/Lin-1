# Lin
Xcode4 plugin showing completion for NSLocalizedString and localizedStringForKey:value:table:

### support macro（by maojj）
  add completion for my custom macro: UI_STRING

  #define UI_STRING(key)          NSLocalizedString(key, nil)

## Installation
Build the Lin, then the plugin will automatically be installed in `~/Library/Application Support/Developer/Shared/Xcode/Plug-ins`.  
Relaunch Xcode and Lin will make your life easier.


## Usage
After installation `Enable Lin` will appear in Edit menu.  

![lin_ss01.png](http://adotout.sakura.ne.jp/github/Lin/lin_ss01.png)

Selecting a line with `NSLocalizedString` or `localizedStringForKey:value:table:` will show completion.

**WARNING Completion will show only there is string in any of the localization files WARNING**

![lin_ss02.png](http://adotout.sakura.ne.jp/github/Lin/lin_ss02.png)

Narrowing down the lists by key.  

![lin_ss03.png](http://adotout.sakura.ne.jp/github/Lin/lin_ss03.png)

You can modify value directly from the popover window. (`.strings` file containing key will be automatically updated) 

![lin_ss04.png](http://adotout.sakura.ne.jp/github/Lin/lin_ss04.png)

## License
*Lin* is released under the **MIT License**, see *LICENSE.txt*.
