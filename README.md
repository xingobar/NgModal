# ng-dialog-simple plugin
ps:required jquery 

<p>include jQuery:</p>
<pre>
    <code>
        < script type="text/javascript" src="./js/jquery-3.3.1.min.js"/>
    </code>
</pre>

<p>include ng_modal.css and modal_animation.css</p>
<pre>
  <code>
     < link rel="stylesheet" href="./css/ng_modal_animation.css"/>
     < link rel="stylesheet" href="./css/ng_modal.css"/>
  </code>
</pre>

<p>include ng_modal.min.js</p>
<pre>
    <code>
        < script type="text/javascript" src="./js/ng_modal.min.js"/>
    </code>
</pre>

<p>description</p>
<pre>
    <code>
        NgModal.[alert|confirm]({
            header:{
                show:boolean, // whether show header or not
                text:.... ,    // show header text
                content:....   // custom modal header content
            }, 
            body:{
                text: ...., // modal body text
                content:...., // custom modal body content
            },
            yes:{
                text: .... // modal footer yes text
            },
            animate: .... ,// show and close animation
            close: .... , // modal footer yes button callback
            backdrop: .... , // backdrop color
            cancel: function({....}), // modal footer cancel button callback
            shadow: boolean, //whether show shadow or not 
            shadowClose:boolean, // when click modal outside whether modal close or not (default true)
            time: ....., // close after xx seconds
            maxWidth: ....(integer), // modal max width
            maxHeight: .... (integer), // modal max height
        })
    </code>
</pre>
