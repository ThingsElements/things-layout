# things-sidebar

## 1.things-routing-behavior.html를 사용하여 Routing 등록 및 설정을 수행한다.

## 2.action에서 제공하는 Url로 Menu를 검색하여 Routing 등록 및 화면 좌측에 메뉴로 제공한다.

## 3.메뉴성이기에 Drawer Attribute가 꼭 필요하다.

Example:

``` html
       <things-sidebar drawer class="layout vertical"
          title="MENU" screens="{{screens}}" action="menus.json?mode=auth">
       </things-sidebar>
```

*****
</br></br>
``

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-alarm/`, where `things-alarm` is the name of the directory containing it.
