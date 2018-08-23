# NgModal 套件開發
附註:此套件需搭配 jquery 
# 暫且只有alert

<p>引入Jquery:</p>

<pre>
    <code>
       < script type="text/javascript" src="./js/jquery-3.3.1.min.js"/> 
    </code>
</pre>

<p>引入ng_modal.css 以及 modal_animation.css</p>
<pre>
    <code>
        < link rel="stylesheet" href="./css/ng_modal_animation.css"/>
        < link rel="stylesheet" href="./css/ng_modal.css"/>
    </code>
</pre>

<p>引入ng_modal.min.js</p>
<pre>
    <code>
        < script type="text/javascript" src="./js/ng_modal.min.js">
    </code>
</pre>

<p>用法</p>
<pre>
    <code>
        NgModal.alert({
            header:boolean, //是否顯示header
            body:{
                text: .... // modal body 內文
            },
            yes:{
                text: .... // 確認按鈕文字
            },
            animate: .... ,// 動畫
            close: .... , //在關閉前想做些什麼事情
        })
    </code>
</pre>