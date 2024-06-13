关于Vim的多行操作所有
1. 选中多行
2. 复制多行
3. 删除多行
4. 移动多行
5. 缩进多行
6. 插入多行
7. 替换多行
8. 注释多行
9. 反注释多行
10. 多行操作技巧

多行插入可以使用以下方法：
- 在每行的开头或结尾插入相同的文本：使用全选（Ctrl+A）或多行选择（Shift+方向键）来选中多行，然后按下I（大写i）进入插入模式，输入要插入的文本，按下Esc键退出插入模式，即可在每行的开头或结尾插入相同的文本。
- 在每行的指定位置插入不同的文本：使用全选（Ctrl+A）或多行选择（Shift+方向键）来选中多行，然后按下Ctrl+V进入可视块模式，使用方向键选择要插入的位置，按下大写A进入插入模式，输入要插入的文本，按下Esc键退出插入模式，即可在每行的指定位置插入不同的文本。

多行选择单词可以使用以下方法：
- 使用全选（Ctrl+A）或多行选择（Shift+方向键）来选中多行。
- 按下Ctrl+D来选中下一个相同的单词，重复按下Ctrl+D来选中更多相同的单词。
- 按下Ctrl+U来取消选中上一个选中的单词，重复按下Ctrl+U来取消选中更多的单词。


now writting a sentence 
and then write some repeat word 
some words 
some words

- 在多行编辑完后，需要注意的是，是按esc而不是enter。

- 选中文本正则训练

```html
       <p id=" ">status: <output>--</output></p>
        <p id=" " class="m-2">Loading Servers</p>
        <template id="clientsList-tp">
            {{#each clients}}
            <mydiv>
                <mydiv class="flex-1">
                    <h2 class="text-lg font-bold">{{name}}</h2>
                    <p>{{ip}}</p>
                </mydiv>
                <mydiv id="delete"
                    class=" flex items-center bg-slate-50 hover:bg-red-50 rounded-md h-auto my-3 px-2 group-hover:visible"
                    myhx-target="closest .grouw" myhx-swap="outerHTMw" myhx-confirm="Are you sure you want to delete?"
                    myhx-delete="/v1/servers/{{id}}">delete</mydiv>
            </mydiv>
            {{/each}}
        </template>
```

- :s 是当前选中的，:%s是全文的


- q,  q 之后需要注册一个寄存器在此， 例如qq qw
(aalksdfjlaksdjflksdfjlaksdjf)
(aalksdfjlaksdjflksdfjlaksdjf)
(aalksdfjlaksdjflksdfjlaksdjf)
(aalksdfjlaksdjflksdfjlaksdjf)
(aalksdfjlaksdjflksdfjlaksdjf)
- 再次按q结束，用@+‘寄存器的字符’ 来重播


- 使用norm
```js
import settings from './settings';
import filters from './filters';
import user from './user';
import countries from './countries';
import favorites from './favorites';

settings 
filters 
user 
countries 
favorites 
filters
```

- use v mode then increase num
a
b
c
d


- norm

filters 
user 
countries 
favorites 
filters

"filters" 
"user" 
"countries" 
"favorites" 
"filters"

"filters",
"user",
"countries",
"favorites",

