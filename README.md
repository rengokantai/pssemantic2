#### pssemantic2
######13 containers
```
ui container
ui text container
ui right aligned container
ui justified container
```
```
mobile only
tablet only
small monitor only
large monitor only
```
######14 segments
```
ui piled segment
ui raised segment
ui segment
```
or:
```
ui horizontal segments > ui padded segment
```
state
```
ui disabled segment
ui loading segment
```
variations
```
ui inverted segment
ui red inverted segment
```
floated
```
right floated green segment
left floated green segment
ui green inverted segment
```
buttons
```
button class (ui primary)
ui secondary
ui tertiary
```
labels
```
<button class='ui labeled button'>
<div class='ui button'>content</div>
<a class="ui basic left pointing label">
</button>
```
icon button
```
<button class='ui icon button'>
<i class='save icon'></i>
</button>
```
labeled icon button
```
<button class='ui labeled icon button'>
<i class='save icon'></i>
save
</button>
```
button styles
```
ui basic button
ui inverted button
```
atached buttons and segments
```
div ui top attached buttons
div ui attached segment
div ui bottom attached bottons
```
massive button
```
ui massive red buttons>ui button
ui massive vertical red buttons>ui button
```
######63 semantic ui modules - progress
```
div.ui.progress#standard>.bar>.progress
```
```
$('#standard').progress({
percent:1
});
```
data indicating
```
div.ui.indicating.progress[data-percent=50]>(.bar>.progress)+.label{uploading}
```
settings
```
autoSuccess showActivity limitValues label random precision total value
```
######65 semantic ui modules - Ratings
```
.ui.star.rating[data-max-rating=5]
.ui.heart.rating[data-max-rating=5]
```
js
```
$('.rating').rating();
```
######66 shapes
```
.ui.shape>.sides>(.active.side>img.ui.small.image)+(.side>img.ui.small.image)
```
js
```
$('.shape').shape();
$('.button').on('click',function(){
  $('.shape').shape('flip up');
});
```
other variations
```
ui cube shape, ui text shape
filp up(left, right, over, back, down), set next side
```
######67 sidebars
```
.ui.sidebar.vertical.inverted.icon.menu>(.item>i.large.home.icon)*3
.pusher>button.ui.primary.button{show}
```
js
```
$('.button').on('click',function(){
  $('.sidebar').sidebar('toggle');
});
```
general settings
```
context exclusive closable dimPage scrollLock returnScroll
```
######69 tab
```
.ui.top.attached.tabular.menu>.active.item[data-tab='a']+.item[data-tab='b']+.item[data-tab='c']
.ui.buttom.attached.active.tab.segment[data-tab='a']+.ui.buttom.attached.tab.segment[data-tab='b']+.ui.buttom.attached.tab.segment[data-tab='c']
```
js
```
$(.tabular.menu .item').tab()
```
settings
```
auto history ignoreFirstLoad eveluateScripts alwaysRefresh cache apiSettings historType path context
```
