##zh_cn 自动翻译,请参照EN下原版理解
<article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-angular-drag-and-drop-lists" class="anchor" href="#angular-drag-and-drop-lists" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="angular-drag-and-drop-lists" data-dst="角拖放列表" style="background: transparent;">角拖放列表</trans></h1>

<p><trans data-src="Angular directives that allow you to build sortable lists with the native HTML5 drag &amp; drop API. The directives can also be nested to bring drag &amp; drop to your WYSIWYG editor, your tree, or whatever fancy structure you are building." data-dst="角指令允许您建立可排序的列表与本地HTML5拖放API。该指令还可以嵌套带拖放到您的所见即所得的编辑，你的树，你是建筑结构或任何幻想。" style="background: transparent;">角指令允许您建立可排序的列表与本地HTML5拖放API。该指令还可以嵌套带拖放到您的所见即所得的编辑，你的树，你是建筑结构或任何幻想。</trans></p>

<h2><a id="user-content-demo" class="anchor" href="#demo" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="Demo" data-dst="演示" style="background: transparent;">演示</trans></h2>

<ul>
<li><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/nested"><trans data-src="Nested Lists" data-dst="嵌套列表" style="background: transparent;">嵌套列表</trans></a></li>
<li><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/simple"><trans data-src="Simple Lists" data-dst="简单列表" style="background: transparent;">简单列表</trans></a></li>
<li><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types"><trans data-src="Typed Lists" data-dst="类型列表">类型列表</trans></a></li>
<li><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Advanced Features" data-dst="先进的功能">先进的功能</trans></a></li>
<li><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/multi"><trans data-src="Multiselection Demo" data-dst="多选演示">多选演示</trans></a></li>
</ul>

<h2><a id="user-content-supported-browsers" class="anchor" href="#supported-browsers" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="Supported browsers" data-dst="支持的浏览器">支持的浏览器</trans></h2>

<p><strong><trans data-src="Touch devices are not supported" data-dst="不支持触摸设备">不支持触摸设备</trans></strong><trans data-src=", because they do not implement the HTML5 drag &amp; drop standard. However, you can use a " data-dst="，因为他们没有实现HTML5拖放标准。然而，你可以使用一个">，因为他们没有实现HTML5拖放标准。然而，你可以使用一个</trans><a href="https://github.com/timruffles/ios-html5-drag-drop-shim"><trans data-src="shim" data-dst="垫片">垫片</trans></a><trans data-src=" to make it work on touch devices as well." data-dst="使它工作在触摸设备以及。">使它工作在触摸设备以及。</trans></p>

<p><trans data-src="Internet Explorer 8 or lower is " data-dst="Internet Explorer 8或更低">Internet Explorer 8或更低</trans><em><trans data-src="not supported" data-dst="不支持">不支持</trans></em><trans data-src=", but all modern browsers are (see changelog for list of tested browsers)." data-dst="，但所有的现代浏览器（见测试浏览器列表的更新）。">，但所有的现代浏览器（见测试浏览器列表的更新）。</trans></p>

<h2><a id="user-content-download--installation" class="anchor" href="#download--installation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="Download &amp; Installation" data-dst="下载和安装">下载和安装</trans></h2>

<ul>
<li><trans data-src="Download " data-dst="下载">下载</trans><code><trans data-src="angular-drag-and-drop-lists.js" data-dst="angular-drag-and-drop-lists.js">angular-drag-and-drop-lists.js</trans></code><trans data-src=" (or the minified version) and include it in your application. If you use bower or npm, just include the " data-dst="（或缩小的版本），包括在你的应用程序。如果你使用的凉亭或NPM，只包括">（或缩小的版本），包括在你的应用程序。如果你使用的凉亭或NPM，只包括</trans><code><trans data-src="angular-drag-and-drop-lists" data-dst="角拖放列表">角拖放列表</trans></code><trans data-src=" package." data-dst="旅行包">旅行包</trans></li>
<li><trans data-src="Add the " data-dst="添加" style="background: transparent;">添加</trans><code><trans data-src="dndLists" data-dst="dndlists">dndlists</trans></code><trans data-src=" module as a dependency to your angular app." data-dst="模块作为一个依赖于你的角的应用。">模块作为一个依赖于你的角的应用。</trans></li>
</ul>

<h2><a id="user-content-dnd-draggable-directive" class="anchor" href="#dnd-draggable-directive" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="dnd-draggable directive" data-dst="DND拖动指令">DND拖动指令</trans></h2>

<p><trans data-src="Use the dnd-draggable directive to make your element draggable" data-dst="使用DND拖动指令让你的元素可拖动">使用DND拖动指令让你的元素可拖动</trans></p>

<p><strong><trans data-src="Attributes" data-dst="特性">特性</trans></strong></p>

<ul>
<li><code><trans data-src="dnd-draggable" data-dst="DND拖动">DND拖动</trans></code><trans data-src=" Required attribute. The value has to be an object that represents the data of the element. In case of a drag and drop operation the object will be serialized and unserialized on the receiving end." data-dst="必需的属性。该值必须是一个对象代表的元素的数据。如果一个拖放操作的对象将被序列化并在接收端不可序列化。">必需的属性。该值必须是一个对象代表的元素的数据。如果一个拖放操作的对象将被序列化并在接收端不可序列化。</trans></li>
<li><code><trans data-src="dnd-effect-allowed" data-dst="DND的影响使">DND的影响使</trans></code><trans data-src=" Use this attribute to limit the operations that can be performed. Options are:

" data-dst="使用此属性来限制可进行的操作。选项：">使用此属性来限制可进行的操作。选项：</trans><ul>
<li><code><trans data-src="move" data-dst="移动">移动</trans></code><trans data-src=" The drag operation will move the element. This is the default" data-dst="拖动操作将移动元素。这是默认的">拖动操作将移动元素。这是默认的</trans></li>
<li><code><trans data-src="copy" data-dst="复制">复制</trans></code><trans data-src=" The drag operation will copy the element. There will be a copy cursor." data-dst="拖动操作将复制元素。会有一个拷贝光标。">拖动操作将复制元素。会有一个拷贝光标。</trans></li>
<li><code><trans data-src="copyMove" data-dst="copymove">copymove</trans></code><trans data-src=" The user can choose between copy and move by pressing the ctrl or shift key.

" data-dst="用户可以选择复制和移动之间按Ctrl或Shift键。">用户可以选择复制和移动之间按Ctrl或Shift键。</trans><ul>
<li><em><trans data-src="Not supported in IE:" data-dst="在IE不支持：">在IE不支持：</trans></em><trans data-src=" In Internet Explorer this option will be the same as " data-dst="在Internet Explorer中这个选项将是相同的">在Internet Explorer中这个选项将是相同的</trans><code><trans data-src="copy" data-dst="复制">复制</trans></code><trans data-src="." data-dst="。">。</trans></li>
<li><em><trans data-src="Not fully supported in Chrome on Windows:" data-dst="不完全支持在Chrome的Windows：">不完全支持在Chrome的Windows：</trans></em><trans data-src=" In the Windows version of Chrome the cursor will always be the move cursor. However, when the user drops an element and has the ctrl key pressed, we will perform a copy anyways." data-dst="在Chrome的光标会移动光标的Windows版本。然而，当用户把元，Ctrl键按下，我们将执行一份吧。">在Chrome的光标会移动光标的Windows版本。然而，当用户把元，Ctrl键按下，我们将执行一份吧。</trans></li>
</ul></li>
<li><trans data-src="HTML5 also specifies the " data-dst="HTML5还指定了">HTML5还指定了</trans><code><trans data-src="link" data-dst="链接">链接</trans></code><trans data-src=" option, but this library does not actively support it yet, so use it at your own risk." data-dst="选项，但是这个库不积极支持它，所以使用它自己的风险。">选项，但是这个库不积极支持它，所以使用它自己的风险。</trans></li>
<li><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
</ul></li>
<li><code><trans data-src="dnd-type" data-dst="DND型">DND型</trans></code><trans data-src=" Use this attribute if you have different kinds of items in your application and you want to limit which items can be dropped into which lists. Combine with dnd-allowed-types on the dnd-list(s). This attribute should evaluate to a string, although this restriction is not enforced (at the moment). " data-dst="使用此属性，如果你有各种不同的应用程序中的项目，你想限制的物品可以放入其中列出。结合DND允许在DND类型列表（S）。此属性应评价为一个字符串，这虽然不强制限制（目前）。">使用此属性，如果你有各种不同的应用程序中的项目，你想限制的物品可以放入其中列出。结合DND允许在DND类型列表（S）。此属性应评价为一个字符串，这虽然不强制限制（目前）。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><code><trans data-src="dnd-disable-if" data-dst="如果禁用-和-">如果禁用-和-</trans></code><trans data-src=" You can use this attribute to dynamically disable the draggability of the element. This is useful if you have certain list items that you don't want to be draggable, or if you want to disable drag &amp; drop completely without having two different code branches (e.g. only allow for admins). " data-dst="你可以使用这个属性来动态地禁用该元素的draggability。如果你有一定的项目清单，你不想被拖动这是有用的，或者如果你想禁用拖放完全不具有两种不同的代码分支（例如只允许管理员）。">你可以使用这个属性来动态地禁用该元素的draggability。如果你有一定的项目清单，你不想被拖动这是有用的，或者如果你想禁用拖放完全不具有两种不同的代码分支（例如只允许管理员）。</trans><em><trans data-src="Note" data-dst="笔记">笔记</trans></em><trans data-src=": If your element is not draggable, the user is probably able to select text or images inside of it. Since a selection is always draggable, this breaks your UI. You most likely want to disable user selection via CSS (see " data-dst="：如果你元素不可拖动，用户可以选择文本或图像里面。既然选择是可拖动，打破你的UI。你可能想禁用用户选择通过CSS（见">：如果你元素不可拖动，用户可以选择文本或图像里面。既然选择是可拖动，打破你的UI。你可能想禁用用户选择通过CSS（见</trans><a href="http://stackoverflow.com/a/4407335"><trans data-src="user-select" data-dst="用户选择">用户选择</trans></a><trans data-src="). " data-dst="）。">）。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
</ul>

<p><strong><trans data-src="Callbacks" data-dst="回调">回调</trans></strong></p>

<ul>
<li><code><trans data-src="dnd-moved" data-dst="DND的感动">DND的感动</trans></code><trans data-src=" Callback that is invoked when the element was moved. Usually you will remove your element from the original list in this callback, since the directive is not doing that for you automatically. The original dragend event will be provided in the local " data-dst="回调被调用，当元素被感动。通常你会在这个回调的原始列表中删除你的元素，因为指令不做自动为你。原dragend事件将在当地提供">回调被调用，当元素被感动。通常你会在这个回调的原始列表中删除你的元素，因为指令不做自动为你。原dragend事件将在当地提供</trans><code><trans data-src="event" data-dst="事件">事件</trans></code><trans data-src=" variable. " data-dst="变量。">变量。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><code><trans data-src="dnd-copied" data-dst="DND - copied">DND - copied</trans></code><trans data-src=" Same as dnd-moved, just that it is called when the element was copied instead of moved. The original dragend event will be provided in the local " data-dst="同和感动，只是它被调用时，元素被复制而不是移动。原dragend事件将在当地提供">同和感动，只是它被调用时，元素被复制而不是移动。原dragend事件将在当地提供</trans><code><trans data-src="event" data-dst="事件">事件</trans></code><trans data-src=" variable. " data-dst="变量。">变量。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><code><trans data-src="dnd-canceled" data-dst="DND取消">DND取消</trans></code><trans data-src=" Callback that is invoked if the element was dragged, but the operation was canceled and the element was not dropped. The original dragend event will be provided in the local event variable. " data-dst="回调被调用，如果元素被拖，但操作被取消，元不是掉了。原dragend事件将在当地事件变量设置。">回调被调用，如果元素被拖，但操作被取消，元不是掉了。原dragend事件将在当地事件变量设置。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><code><trans data-src="dnd-dragstart" data-dst="DND拖曳开始">DND拖曳开始</trans></code><trans data-src=" Callback that is invoked when the element was dragged. The original dragstart event will be provided in the local " data-dst="回调被调用当元素被拖。原来的拖曳开始活动将在当地提供">回调被调用当元素被拖。原来的拖曳开始活动将在当地提供</trans><code><trans data-src="event" data-dst="事件">事件</trans></code><trans data-src=" variable. " data-dst="变量。">变量。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><code><trans data-src="dnd-dragend" data-dst="DND dragend">DND dragend</trans></code><trans data-src=" Callback that is invoked when the drag operation ended. Available local variables are " data-dst="回调被调用的拖动操作结束时。使用局部变量">回调被调用的拖动操作结束时。使用局部变量</trans><code><trans data-src="event" data-dst="事件">事件</trans></code><trans data-src=" and " data-dst="和">和</trans><code><trans data-src="dropEffect" data-dst="dropeffect">dropeffect</trans></code><trans data-src=". " data-dst="。">。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><code><trans data-src="dnd-selected" data-dst="DND的选择">DND的选择</trans></code><trans data-src=" Callback that is invoked when the element was clicked but not dragged. The original click event will be provided in the local " data-dst="回调被调用，当元素被点击而不拖。原来的单击事件将在当地提供">回调被调用，当元素被点击而不拖。原来的单击事件将在当地提供</trans><code><trans data-src="event" data-dst="事件">事件</trans></code><trans data-src=" variable. " data-dst="变量。">变量。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/nested"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
</ul>

<p><strong><trans data-src="CSS classes" data-dst="CSS类">CSS类</trans></strong></p>

<ul>
<li><code><trans data-src="dndDragging" data-dst="dnddragging">dnddragging</trans></code><trans data-src=" This class will be added to the element while the element is being dragged. It will affect both the element you see while dragging and the source element that stays at it's position. Do not try to hide the source element with this class, because that will abort the drag operation." data-dst="这类将被添加到元素，元素被拖。它会影响你在拖动元素看，源元件保持在它的位置。不要试图用这类隐藏的源元素，因为这将取消拖动操作。">这类将被添加到元素，元素被拖。它会影响你在拖动元素看，源元件保持在它的位置。不要试图用这类隐藏的源元素，因为这将取消拖动操作。</trans></li>
<li><code><trans data-src="dndDraggingSource" data-dst="dnddraggingsource">dnddraggingsource</trans></code><trans data-src=" This class will be added to the element after the drag operation was started, meaning it only affects the original element that is still at it's source position, and not the &quot;element&quot; that the user is dragging with his mouse pointer" data-dst="这类将在拖动操作开始添加的元素，它只影响那些仍然是它的源位置的原始元素，而不是“元”，用户用自己的鼠标指针拖动">这类将在拖动操作开始添加的元素，它只影响那些仍然是它的源位置的原始元素，而不是“元”，用户用自己的鼠标指针拖动</trans></li>
</ul>

<h2><a id="user-content-dnd-list-directive" class="anchor" href="#dnd-list-directive" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="dnd-list directive" data-dst="DND列表指令">DND列表指令</trans></h2>

<p><trans data-src="Use the dnd-list attribute to make your list element a dropzone. Usually you will add a single li element as child with the ng-repeat directive. If you don't do that, we will not be able to position the dropped element correctly. If you want your list to be sortable, also add the dnd-draggable directive to your li element(s). Both the dnd-list and it's direct children must have position: relative CSS style, otherwise the positioning algorithm will not be able to determine the correct placeholder position in all browsers." data-dst="使用“列表属性使列表元素的悬浮窗。你通常会添加一个锂元素与NG重复指令的孩子。如果你不这样做，我们将无法正确定位降元。如果你想让你的列表进行排序，同时加入DND拖动指令你的锂元素（S）。无论是DND列表和它的直接的儿童必须有相对位置：CSS样式，否则定位算法将无法确定在所有浏览器中正确的占位符的位置。">使用“列表属性使列表元素的悬浮窗。你通常会添加一个锂元素与NG重复指令的孩子。如果你不这样做，我们将无法正确定位降元。如果你想让你的列表进行排序，同时加入DND拖动指令你的锂元素（S）。无论是DND列表和它的直接的儿童必须有相对位置：CSS样式，否则定位算法将无法确定在所有浏览器中正确的占位符的位置。</trans></p>

<p><strong><trans data-src="Attributes" data-dst="特性">特性</trans></strong></p>

<ul>
<li><code><trans data-src="dnd-list" data-dst="DND的名单">DND的名单</trans></code><trans data-src=" Required attribute. The value has to be the array in which the data of the dropped element should be inserted." data-dst="必需的属性。值必须是数组的元素的数据应插入了。">必需的属性。值必须是数组的元素的数据应插入了。</trans></li>
<li><code><trans data-src="dnd-allowed-types" data-dst="DND允许的类型">DND允许的类型</trans></code><trans data-src=" Optional array of allowed item types. When used, only items that had a matching dnd-type attribute will be dropable. " data-dst="允许项目类型可选阵列。使用时，仅当项目有一个匹配的DND类型属性将可抛。">允许项目类型可选阵列。使用时，仅当项目有一个匹配的DND类型属性将可抛。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><code><trans data-src="dnd-disable-if" data-dst="如果禁用-和-">如果禁用-和-</trans></code><trans data-src=" Optional boolean expression. When it evaluates to true, no dropping into the list is possible. Note that this also disables rearranging items inside the list. " data-dst="可选的布尔表达式。当它的值为true，没有进入名单是可能的。请注意，这也将禁用物品名单里的重排。">可选的布尔表达式。当它的值为true，没有进入名单是可能的。请注意，这也将禁用物品名单里的重排。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><code><trans data-src="dnd-horizontal-list" data-dst="DND水平表">DND水平表</trans></code><trans data-src=" Optional boolean expression. When it evaluates to true, the positioning algorithm will use the left and right halfs of the list items instead of the upper and lower halfs. " data-dst="可选的布尔表达式。当它的值为true，定位算法将使用左和列表项而不是上下半好半。">可选的布尔表达式。当它的值为true，定位算法将使用左和列表项而不是上下半好半。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><code><trans data-src="dnd-external-sources" data-dst="DND的外部来源">DND的外部来源</trans></code><trans data-src=" Optional boolean expression. When it evaluates to true, the list accepts drops from sources outside of the current browser tab. This allows to drag and drop accross different browser tabs. Note that this will allow to drop arbitrary text into the list, thus it is highly recommended to implement the dnd-drop callback to check the incoming element for sanity. Furthermore, the dnd-type of external sources can not be determined, therefore do not rely on restrictions of dnd-allowed-type. Also note that this feature does not work very well in Internet Explorer. " data-dst="可选的布尔表达式。当它的值为true，列表接受从当前浏览器标签外部来源滴。这允许拖放在不同浏览器的标签。请注意，这将允许下降到任意文本列表，因此建议实施DND下降回调检查传入的元素是。此外，外部来源的DND类型无法确定，因此不依靠DND允许的类型限制。还请注意，此功能不在Internet Explorer中很好地工作。">可选的布尔表达式。当它的值为true，列表接受从当前浏览器标签外部来源滴。这允许拖放在不同浏览器的标签。请注意，这将允许下降到任意文本列表，因此建议实施DND下降回调检查传入的元素是。此外，外部来源的DND类型无法确定，因此不依靠DND允许的类型限制。还请注意，此功能不在Internet Explorer中很好地工作。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
</ul>

<p><strong><trans data-src="Callbacks" data-dst="回调">回调</trans></strong></p>

<ul>
<li><code><trans data-src="dnd-dragover" data-dst="DND DragOver">DND DragOver</trans></code><trans data-src=" Optional expression that is invoked when an element is dragged over the list. If the expression is set, but does not return true, the element is not allowed to be dropped. The following variables will be available:

" data-dst="可选的表达式，当调用一个元素拖到列表。如果表达式集，但不返回true，元素是不允许被删除。下列变量将可：">可选的表达式，当调用一个元素拖到列表。如果表达式集，但不返回true，元素是不允许被删除。下列变量将可：</trans><ul>
<li><code><trans data-src="event" data-dst="事件">事件</trans></code><trans data-src=" The original dragover event sent by the browser." data-dst="由浏览器发送的原始DragOver事件。">由浏览器发送的原始DragOver事件。</trans></li>
<li><code><trans data-src="index" data-dst="指数">指数</trans></code><trans data-src=" The position in the list at which the element would be dropped." data-dst="位置在列表中的元素将下降。">位置在列表中的元素将下降。</trans></li>
<li><code><trans data-src="type" data-dst="类型">类型</trans></code><trans data-src=" The " data-dst="这个">这个</trans><code><trans data-src="dnd-type" data-dst="DND型">DND型</trans></code><trans data-src=" set on the dnd-draggable, or undefined if unset." data-dst="设置DND的拖动，或如果未设置。">设置DND的拖动，或如果未设置。</trans></li>
<li><code><trans data-src="external" data-dst="外部的">外部的</trans></code><trans data-src=" Whether the element was dragged from an external source. See " data-dst="元素是否是从外部源拖。看到">元素是否是从外部源拖。看到</trans><code><trans data-src="dnd-external-sources" data-dst="DND的外部来源">DND的外部来源</trans></code><trans data-src="." data-dst="。">。</trans></li>
<li><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
</ul></li>
<li><code><trans data-src="dnd-drop" data-dst="DND下降">DND下降</trans></code><trans data-src=" Optional expression that is invoked when an element is dropped on the list.

" data-dst="可选的表达式，当调用元素到列表。">可选的表达式，当调用元素到列表。</trans><ul>
<li><trans data-src="The following variables will be available:

" data-dst="下列变量将可：">下列变量将可：</trans><ul>
<li><code><trans data-src="event" data-dst="事件">事件</trans></code><trans data-src=" The original drop event sent by the browser." data-dst="最初的感觉by the浏览器拖放事件。">最初的感觉by the浏览器拖放事件。</trans></li>
<li><code><trans data-src="index" data-dst="指数">指数</trans></code><trans data-src=" The position in the list at which the element would be dropped." data-dst="位置在列表中的元素将下降。">位置在列表中的元素将下降。</trans></li>
<li><code><trans data-src="item" data-dst="项目">项目</trans></code><trans data-src=" The transferred object." data-dst="转移对象。">转移对象。</trans></li>
<li><code><trans data-src="type" data-dst="类型">类型</trans></code><trans data-src=" The dnd-type set on the dnd-draggable, or undefined if unset." data-dst="DND类型设置DND的拖动，或如果未设置。">DND类型设置DND的拖动，或如果未设置。</trans></li>
<li><code><trans data-src="external" data-dst="外部的">外部的</trans></code><trans data-src=" Whether the element was dragged from an external source. See " data-dst="元素是否是从外部源拖。看到">元素是否是从外部源拖。看到</trans><code><trans data-src="dnd-external-sources" data-dst="DND的外部来源">DND的外部来源</trans></code><trans data-src="." data-dst="。">。</trans></li>
</ul></li>
<li><trans data-src="The return value determines the further handling of the drop:

" data-dst="返回值确定的下降进一步处理：">返回值确定的下降进一步处理：</trans><ul>
<li><code><trans data-src="false" data-dst="假">假</trans></code><trans data-src=" The drop will be canceled and the element won't be inserted." data-dst="的下降将取消，元素不会被插入。">的下降将取消，元素不会被插入。</trans></li>
<li><code><trans data-src="true" data-dst="真正的">真正的</trans></code><trans data-src=" Signalises that the drop is allowed, but the dnd-drop callback will take care of inserting the element." data-dst="signalises，下降是允许的，但“降回调会照顾插入元素。">signalises，下降是允许的，但“降回调会照顾插入元素。</trans></li>
<li><trans data-src="Otherwise: All other return values will be treated as the object to insert into the array. In most cases you simply want to return the " data-dst="其他：其他所有的返回值将被插入到数组对象。在大多数情况下，你只想要回">其他：其他所有的返回值将被插入到数组对象。在大多数情况下，你只想要回</trans><code><trans data-src="item" data-dst="项目">项目</trans></code><trans data-src=" parameter, but there are no restrictions on what you can return." data-dst="参数，但没有限制你可以返回。">参数，但没有限制你可以返回。</trans></li>
</ul></li>
</ul></li>
<li><code><trans data-src="dnd-inserted" data-dst="DND插入">DND插入</trans></code><trans data-src=" Optional expression that is invoked after a drop if the element was actually inserted into the list. The same local variables as for " data-dst="可选的表达式，调用下降如果元素实际上是插入到列表后。相同的局部变量作为">可选的表达式，调用下降如果元素实际上是插入到列表后。相同的局部变量作为</trans><code><trans data-src="dnd-drop" data-dst="DND下降">DND下降</trans></code><trans data-src=" will be available. Note that for reorderings inside the same list the old element will still be in the list due to the fact that " data-dst="将可。注意：在同一列表reorderings老元仍将在列表中由于">将可。注意：在同一列表reorderings老元仍将在列表中由于</trans><code><trans data-src="dnd-moved" data-dst="DND的感动">DND的感动</trans></code><trans data-src=" was not called yet. " data-dst="还未被召唤。">还未被召唤。</trans><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
</ul>

<p><strong><trans data-src="CSS classes" data-dst="CSS类">CSS类</trans></strong></p>

<ul>
<li><code><trans data-src="dndPlaceholder" data-dst="dndplaceholder">dndplaceholder</trans></code><trans data-src=" When an element is dragged over the list, a new placeholder child element will be added. This element is of type " data-dst="当一个元素被拖到列表中，一个新的子元素将添加占位符。这个元素的类型是">当一个元素被拖到列表中，一个新的子元素将添加占位符。这个元素的类型是</trans><code><trans data-src="li" data-dst="锂">锂</trans></code><trans data-src=" and has the class " data-dst="具有类">具有类</trans><code><trans data-src="dndPlaceholder" data-dst="dndplaceholder">dndplaceholder</trans></code><trans data-src=" set. Alternatively, you can define your own placeholder by creating a child element with " data-dst="配置另外，你可以通过创建子元素定义自己的占位符">配置另外，你可以通过创建子元素定义自己的占位符</trans><code><trans data-src="dndPlaceholder" data-dst="dndplaceholder">dndplaceholder</trans></code><trans data-src=" class." data-dst="类">类</trans></li>
<li><code><trans data-src="dndDragover" data-dst="dnddragover">dnddragover</trans></code><trans data-src=" This class will be added to the list while an element is being dragged over the list." data-dst="这个类将被添加到列表中，一个元素被拖到列表。">这个类将被添加到列表中，一个元素被拖到列表。</trans></li>
</ul>

<h2><a id="user-content-dnd-nodrag-directive" class="anchor" href="#dnd-nodrag-directive" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="dnd-nodrag directive" data-dst="nodrag DND的指令。">nodrag DND的指令。</trans></h2>

<p><trans data-src="Use the " data-dst="使用">使用</trans><code><trans data-src="dnd-nodrag" data-dst="nodrag DND。">nodrag DND。</trans></code><trans data-src=" attribute inside of " data-dst="属性里面">属性里面</trans><code><trans data-src="dnd-draggable" data-dst="DND拖动">DND拖动</trans></code><trans data-src=" elements to prevent them from starting drag operations. This is especially useful if you want to use input elements inside of " data-dst="元素来防止他们开始拖动操作。如果你想在使用输入元素，这是特别有用的">元素来防止他们开始拖动操作。如果你想在使用输入元素，这是特别有用的</trans><code><trans data-src="dnd-draggable" data-dst="DND拖动">DND拖动</trans></code><trans data-src=" elements or create specific handle elements." data-dst="元素或创建特定的处理单元。">元素或创建特定的处理单元。</trans></p>

<p><strong><trans data-src="Note:" data-dst="笔记">笔记</trans></strong><trans data-src=" This directive does not work in Internet Explorer 9." data-dst="本指令不在Internet Explorer 9工作。">本指令不在Internet Explorer 9工作。</trans></p>

<p><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types"><trans data-src="Demo" data-dst="演示">演示</trans></a></p>

<h2><a id="user-content-dnd-handle-directive" class="anchor" href="#dnd-handle-directive" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="dnd-handle directive" data-dst="DND处理指令">DND处理指令</trans></h2>

<p><trans data-src="Use the " data-dst="使用">使用</trans><code><trans data-src="dnd-handle" data-dst="DND处理">DND处理</trans></code><trans data-src=" directive within a " data-dst="指令在一个">指令在一个</trans><code><trans data-src="dnd-nodrag" data-dst="nodrag DND。">nodrag DND。</trans></code><trans data-src=" element in order to allow dragging of that element after all. Therefore, by combining " data-dst="元为了让拖动元素毕竟。因此，结合">元为了让拖动元素毕竟。因此，结合</trans><code><trans data-src="dnd-nodrag" data-dst="nodrag DND。">nodrag DND。</trans></code><trans data-src=" and " data-dst="和">和</trans><code><trans data-src="dnd-handle" data-dst="DND处理">DND处理</trans></code><trans data-src=" you can allow " data-dst="你可以让">你可以让</trans><code><trans data-src="dnd-draggable" data-dst="DND拖动">DND拖动</trans></code><trans data-src=" elements to only be dragged via specific " data-dst="元素只能拖着通过特定的">元素只能拖着通过特定的</trans><em><trans data-src="handle" data-dst="手柄">手柄</trans></em><trans data-src=" elements." data-dst="元素.">元素.</trans></p>

<p><strong><trans data-src="Note:" data-dst="笔记">笔记</trans></strong><trans data-src=" Internet Explorer will show the handle element as drag image instead of the " data-dst="Internet Explorer将显示处理单元而不是拖动图像">Internet Explorer将显示处理单元而不是拖动图像</trans><code><trans data-src="dnd-draggable" data-dst="DND拖动">DND拖动</trans></code><trans data-src=" element. You can work around this by styling the handle element differently when it is being dragged. Use the CSS selector " data-dst="元。你可以通过造型元素的处理不同，当它被拖。使用CSS选择器">元。你可以通过造型元素的处理不同，当它被拖。使用CSS选择器</trans><code><trans data-src=".dndDragging:not(.dndDraggingSource) [dnd-handle]" data-dst=".dnddragging：not（DND .dnddraggingsource handle）[ - ]">.dnddragging：not（DND .dnddraggingsource handle）[ - ]</trans></code><trans data-src=" for that." data-dst="那。">那。</trans></p>

<p><a href="http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types"><trans data-src="Demo" data-dst="演示">演示</trans></a></p>

<h2><a id="user-content-required-css-styles" class="anchor" href="#required-css-styles" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="Required CSS styles" data-dst="所需的CSS样式">所需的CSS样式</trans></h2>

<p><trans data-src="Both the dnd-list and it's children require relative positioning, so that the directive can determine the mouse position relative to the list and thus calculate the correct drop position." data-dst="无论是DND列表和它的孩子需要相对定位，使指令能确定鼠标的位置相对于列表，从而计算出正确的放置位置。">无论是DND列表和它的孩子需要相对定位，使指令能确定鼠标的位置相对于列表，从而计算出正确的放置位置。</trans></p>

<pre><trans data-src="ul[dnd-list], ul[dnd-list] > li {
    position: relative;
}
" data-dst="UL [表]、[ DND，UL列表>里
相对位置：{ } 
">UL [表]、[ DND，UL列表&gt;里
相对位置：{ } 
</trans></pre>

<h2><a id="user-content-why-another-drag--drop-library" class="anchor" href="#why-another-drag--drop-library" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="Why another drag &amp; drop library?" data-dst="为什么一个拖放库？">为什么一个拖放库？</trans></h2>

<p><trans data-src="There are tons of other drag &amp; drop libraries out there, but none of them met my three requirements:" data-dst="有其他拖放库很多，但他们都不符合我的要求三：">有其他拖放库很多，但他们都不符合我的要求三：</trans></p>

<ul>
<li><strong><trans data-src="Angular:" data-dst="角：">角：</trans></strong><trans data-src=" If you use angular.js, you really don't want to throw a bunch of jQuery into your app. Instead you want to use libraries that were build the &quot;angular way&quot; and support " data-dst="如果你使用angular.js，你真的不想把一堆jQuery到你的应用程序。你要使用图书馆，建立“角”的方式，支持">如果你使用angular.js，你真的不想把一堆jQuery到你的应用程序。你要使用图书馆，建立“角”的方式，支持</trans><strong><trans data-src="two-way data binding" data-dst="双向数据绑定">双向数据绑定</trans></strong><trans data-src=" to update your data model automatically." data-dst="更新你的数据模型自动。">更新你的数据模型自动。</trans></li>
<li><strong><trans data-src="Nested lists:" data-dst="嵌套列表：">嵌套列表：</trans></strong><trans data-src=" If you want to build a " data-dst="如果你想建立一个">如果你想建立一个</trans><strong><trans data-src="WYSIWYG editor" data-dst="WYSIWYG编辑器">WYSIWYG编辑器</trans></strong><trans data-src=" or have some fancy " data-dst="或者有一些幻想">或者有一些幻想</trans><strong><trans data-src="tree structure" data-dst="树结构">树结构</trans></strong><trans data-src=", the library has to support nested lists." data-dst="，图书馆也支持嵌套列表。">，图书馆也支持嵌套列表。</trans></li>
<li><strong><trans data-src="HTML5 drag &amp; drop:" data-dst="HTML5拖放：">HTML5拖放：</trans></strong> Most drag &amp; drop applications you'll find on the internet use pure JavaScript drag &amp; drop. But with the arrival of HTML5 we can delegate most of the work to the browser. For example: If you want to show the user what he's currently dragging, you'll have to update the position of the element all the time and set it below the mouse pointer. In HTML5 the browser will do that for you! But you can not only save code lines, you can also offer a more <strong><trans data-src="native user experience" data-dst="本地用户体验">本地用户体验</trans></strong><trans data-src=": If you click on an element in a pure JavaScript drag &amp; drop implementation, it will usually start the drag operation. But remember what happens when you click an icon on your desktop: The icon will be selected, not dragged! This is the native behaviour you can bring to your web application with HTML5." data-dst="：如果你点击一个元素在一个纯JavaScript拖放实现，它通常会开始拖动操作。但是记住，当你点击一个图标在您的桌面上的图标：将被选中，不拖！这是当地的行为，你可以为你的Web应用HTML5。">：如果你点击一个元素在一个纯JavaScript拖放实现，它通常会开始拖动操作。但是记住，当你点击一个图标在您的桌面上的图标：将被选中，不拖！这是当地的行为，你可以为你的Web应用HTML5。</trans></li>
</ul>

<p><trans data-src="If this doesn't fit your requirements, check out one of the other awesome drag &amp; drop libraries:" data-dst="如果这不符合你的要求，看看另一个可怕的拖放库：">如果这不符合你的要求，看看另一个可怕的拖放库：</trans></p>

<ul>
<li><a href="https://github.com/JimLiu/angular-ui-tree"><trans data-src="angular-ui-tree" data-dst="角UI树">角UI树</trans></a><trans data-src=": Very similar to this library, but does not use the HTML5 API. Therefore you need to write some more markup to see what you are dragging and it will create another DOM node that you have to style. However, if you plan to support touch devices this is probably your best choice." data-dst="：这个图书馆很相似，但不使用HTML5的API。因此你需要写一些标记能够看到你拖着它会创建一个DOM节点，你的风格。然而，如果你计划支持触摸设备，这可能是你最好的选择。">：这个图书馆很相似，但不使用HTML5的API。因此你需要写一些标记能够看到你拖着它会创建一个DOM节点，你的风格。然而，如果你计划支持触摸设备，这可能是你最好的选择。</trans></li>
<li><a href="https://github.com/ganarajpr/angular-dragdrop"><trans data-src="angular-dragdrop" data-dst="角拖放">角拖放</trans></a><trans data-src=": One of many libraries with the same name. This one uses the HTML5 API, but if you want to build (nested) sortable lists, you're on your own, because it does not calculate the correct element position for you." data-dst="许多图书馆：一个具有相同名称的。这一个使用HTML5的API，但是如果你想建立（嵌套）排序的列表，你对你自己，因为它不会为你计算正确的位置。">许多图书馆：一个具有相同名称的。这一个使用HTML5的API，但是如果你想建立（嵌套）排序的列表，你对你自己，因为它不会为你计算正确的位置。</trans></li>
<li><a href="https://www.google.de/search?q=angular+drag+and+drop"><trans data-src="more..." data-dst="更多">更多</trans></a></li>
</ul>

<h2><a id="user-content-license" class="anchor" href="#license" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><trans data-src="License" data-dst="许可证">许可证</trans></h2>

<p><trans data-src="Copyright (c) 2014 " data-dst="版权所有（C）2014年">版权所有（C）2014年</trans><a href="mailto:marcel@juenemann.cc"><trans data-src="Marcel Juenemann" data-dst="马塞尔juenemann">马塞尔juenemann</trans></a></p>

<p><trans data-src="Copyright (c) 2014-2016 Google Inc." data-dst="版权所有（C）谷歌2014至2016年。">版权所有（C）谷歌2014至2016年。</trans></p>

<p><trans data-src="This is not an official Google product (experimental or otherwise), it is just code that happens to be owned by Google." data-dst="这不是一个官方的谷歌产品（实验或其他），它只是代码，是谷歌旗下的。">这不是一个官方的谷歌产品（实验或其他），它只是代码，是谷歌旗下的。</trans></p>

<p><a href="https://raw.githubusercontent.com/marceljuenemann/angular-drag-and-drop-lists/master/LICENSE"><trans data-src="MIT License" data-dst="MIT许可证">MIT许可证</trans></a></p>
</article>

##EN
angular-drag-and-drop-lists
===========================
Angular directives that allow you to build sortable lists with the native HTML5 drag & drop API. The directives can also be nested to bring drag & drop to your WYSIWYG editor, your tree, or whatever fancy structure you are building.

## Demo
* [Nested Lists](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/nested)
* [Simple Lists](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/simple)
* [Typed Lists](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types)
* [Advanced Features](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)
* [Multiselection Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/multi)


## Supported browsers

**Touch devices are not supported**, because they do not implement the HTML5 drag & drop standard. However, you can use a [shim](https://github.com/timruffles/ios-html5-drag-drop-shim) to make it work on touch devices as well.

Internet Explorer 8 or lower is *not supported*, but all modern browsers are (see changelog for list of tested browsers).


## Download & Installation
* Download `angular-drag-and-drop-lists.js` (or the minified version) and include it in your application. If you use bower or npm, just include the `angular-drag-and-drop-lists` package.
* Add the `dndLists` module as a dependency to your angular app.

## dnd-draggable directive
Use the dnd-draggable directive to make your element draggable

**Attributes**
* `dnd-draggable` Required attribute. The value has to be an object that represents the data of the element. In case of a drag and drop operation the object will be serialized and unserialized on the receiving end.
* `dnd-effect-allowed` Use this attribute to limit the operations that can be performed. Options are:
    * `move` The drag operation will move the element. This is the default
    * `copy` The drag operation will copy the element. There will be a copy cursor.
    * `copyMove` The user can choose between copy and move by pressing the ctrl or shift key.
        * *Not supported in IE:* In Internet Explorer this option will be the same as `copy`.
        * *Not fully supported in Chrome on Windows:* In the Windows version of Chrome the cursor will always be the move cursor. However, when the user drops an element and has the ctrl key pressed, we will perform a copy anyways.
    * HTML5 also specifies the `link` option, but this library does not actively support it yet, so use it at your own risk.
    * [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)
* `dnd-type` Use this attribute if you have different kinds of items in your application and you want to limit which items can be dropped into which lists. Combine with dnd-allowed-types on the dnd-list(s). This attribute should evaluate to a string, although this restriction is not enforced (at the moment). [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types)
* `dnd-disable-if` You can use this attribute to dynamically disable the draggability of the element. This is useful if you have certain list items that you don't want to be draggable, or if you want to disable drag & drop completely without having two different code branches (e.g. only allow for admins). *Note*: If your element is not draggable, the user is probably able to select text or images inside of it. Since a selection is always draggable, this breaks your UI. You most likely want to disable user selection via CSS (see [user-select](http://stackoverflow.com/a/4407335)). [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types)

**Callbacks**
* `dnd-moved` Callback that is invoked when the element was moved. Usually you will remove your element from the original list in this callback, since the directive is not doing that for you automatically. The original dragend event will be provided in the local `event` variable. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)
* `dnd-copied` Same as dnd-moved, just that it is called when the element was copied instead of moved. The original dragend event will be provided in the local `event` variable. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)
* `dnd-canceled` Callback that is invoked if the element was dragged, but the operation was canceled and the element was not dropped. The original dragend event will be provided in the local event variable. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)
* `dnd-dragstart` Callback that is invoked when the element was dragged. The original dragstart event will be provided in the local `event` variable. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)
* `dnd-dragend` Callback that is invoked when the drag operation ended. Available local variables are `event` and `dropEffect`. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)
* `dnd-selected` Callback that is invoked when the element was clicked but not dragged. The original click event will be provided in the local `event` variable. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/nested)

**CSS classes**
* `dndDragging` This class will be added to the element while the element is being dragged. It will affect both the element you see while dragging and the source element that stays at it's position. Do not try to hide the source element with this class, because that will abort the drag operation.
* `dndDraggingSource` This class will be added to the element after the drag operation was started, meaning it only affects the original element that is still at it's source position, and not the "element" that the user is dragging with his mouse pointer

## dnd-list directive

Use the dnd-list attribute to make your list element a dropzone. Usually you will add a single li element as child with the ng-repeat directive. If you don't do that, we will not be able to position the dropped element correctly. If you want your list to be sortable, also add the dnd-draggable directive to your li element(s). Both the dnd-list and it's direct children must have position: relative CSS style, otherwise the positioning algorithm will not be able to determine the correct placeholder position in all browsers.

**Attributes**
* `dnd-list` Required attribute. The value has to be the array in which the data of the dropped element should be inserted.
* `dnd-allowed-types` Optional array of allowed item types. When used, only items that had a matching dnd-type attribute will be dropable. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types)
* `dnd-disable-if` Optional boolean expression. When it evaluates to true, no dropping into the list is possible. Note that this also disables rearranging items inside the list. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types)
* `dnd-horizontal-list` Optional boolean expression. When it evaluates to true, the positioning algorithm will use the left and right halfs of the list items instead of the upper and lower halfs. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)
* `dnd-external-sources` Optional boolean expression. When it evaluates to true, the list accepts drops from sources outside of the current browser tab. This allows to drag and drop accross different browser tabs. Note that this will allow to drop arbitrary text into the list, thus it is highly recommended to implement the dnd-drop callback to check the incoming element for sanity. Furthermore, the dnd-type of external sources can not be determined, therefore do not rely on restrictions of dnd-allowed-type. Also note that this feature does not work very well in Internet Explorer. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)

**Callbacks**
* `dnd-dragover` Optional expression that is invoked when an element is dragged over the list. If the expression is set, but does not return true, the element is not allowed to be dropped. The following variables will be available:
    * `event` The original dragover event sent by the browser.
    * `index` The position in the list at which the element would be dropped.
    * `type` The `dnd-type` set on the dnd-draggable, or undefined if unset.
    * `external` Whether the element was dragged from an external source. See `dnd-external-sources`.
    * [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)
* `dnd-drop` Optional expression that is invoked when an element is dropped on the list.
    * The following variables will be available:
       * `event` The original drop event sent by the browser.
       * `index` The position in the list at which the element would be dropped.
       * `item` The transferred object.
       * `type` The dnd-type set on the dnd-draggable, or undefined if unset.
       * `external` Whether the element was dragged from an external source. See `dnd-external-sources`.
    * The return value determines the further handling of the drop:
      * `false` The drop will be canceled and the element won't be inserted.
      * `true` Signalises that the drop is allowed, but the dnd-drop callback will take care of inserting the element.
      * Otherwise: All other return values will be treated as the object to insert into the array. In most cases you simply want to return the `item` parameter, but there are no restrictions on what you can return.
* `dnd-inserted` Optional expression that is invoked after a drop if the element was actually inserted into the list. The same local variables as for `dnd-drop` will be available. Note that for reorderings inside the same list the old element will still be in the list due to the fact that `dnd-moved` was not called yet. [Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/advanced)

**CSS classes**
* `dndPlaceholder` When an element is dragged over the list, a new placeholder child element will be added. This element is of type `li` and has the class `dndPlaceholder` set. Alternatively, you can define your own placeholder by creating a child element with `dndPlaceholder` class.
* `dndDragover` This class will be added to the list while an element is being dragged over the list.

## dnd-nodrag directive

Use the `dnd-nodrag` attribute inside of `dnd-draggable` elements to prevent them from starting drag operations. This is especially useful if you want to use input elements inside of `dnd-draggable` elements or create specific handle elements.

**Note:** This directive does not work in Internet Explorer 9.

[Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types)

## dnd-handle directive

Use the `dnd-handle` directive within a `dnd-nodrag` element in order to allow dragging of that element after all. Therefore, by combining `dnd-nodrag` and `dnd-handle` you can allow `dnd-draggable` elements to only be dragged via specific *handle* elements.

**Note:** Internet Explorer will show the handle element as drag image instead of the `dnd-draggable` element. You can work around this by styling the handle element differently when it is being dragged. Use the CSS selector `.dndDragging:not(.dndDraggingSource) [dnd-handle]` for that.

[Demo](http://marceljuenemann.github.io/angular-drag-and-drop-lists/demo/#/types)

## Required CSS styles
Both the dnd-list and it's children require relative positioning, so that the directive can determine the mouse position relative to the list and thus calculate the correct drop position.

<pre>
ul[dnd-list], ul[dnd-list] > li {
    position: relative;
}
</pre>



## Why another drag & drop library?
There are tons of other drag & drop libraries out there, but none of them met my three requirements:

* **Angular:** If you use angular.js, you really don't want to throw a bunch of jQuery into your app. Instead you want to use libraries that were build the "angular way" and support **two-way data binding** to update your data model automatically.
* **Nested lists:** If you want to build a **WYSIWYG editor** or have some fancy **tree structure**, the library has to support nested lists.
* **HTML5 drag & drop:** Most drag & drop applications you'll find on the internet use pure JavaScript drag & drop. But with the arrival of HTML5 we can delegate most of the work to the browser. For example: If you want to show the user what he's currently dragging, you'll have to update the position of the element all the time and set it below the mouse pointer. In HTML5 the browser will do that for you! But you can not only save code lines, you can also offer a more **native user experience**: If you click on an element in a pure JavaScript drag & drop implementation, it will usually start the drag operation. But remember what happens when you click an icon on your desktop: The icon will be selected, not dragged! This is the native behaviour you can bring to your web application with HTML5.

If this doesn't fit your requirements, check out one of the other awesome drag & drop libraries:

* [angular-ui-tree](https://github.com/JimLiu/angular-ui-tree): Very similar to this library, but does not use the HTML5 API. Therefore you need to write some more markup to see what you are dragging and it will create another DOM node that you have to style. However, if you plan to support touch devices this is probably your best choice.
* [angular-dragdrop](https://github.com/ganarajpr/angular-dragdrop): One of many libraries with the same name. This one uses the HTML5 API, but if you want to build (nested) sortable lists, you're on your own, because it does not calculate the correct element position for you.
* [more...](https://www.google.de/search?q=angular+drag+and+drop)


## License

Copyright (c) 2014 [Marcel Juenemann](mailto:marcel@juenemann.cc)

Copyright (c) 2014-2016 Google Inc.

This is not an official Google product (experimental or otherwise), it is just code that happens to be owned by Google.

[MIT License](https://raw.githubusercontent.com/marceljuenemann/angular-drag-and-drop-lists/master/LICENSE)
