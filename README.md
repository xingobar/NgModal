# ng-dialog-simple plugin
ps:required jquery 

<p>引入Jquery:</p>

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
                text:....     // show header text
            }, 
            body:{
                text: .... // modal body text
            },
            yes:{
                text: .... // modal footer yes text
            },
            animate: .... ,// show and close animation
            close: .... , // modal footer yes button callback
            backdrop: .... , // backdrop color
            cancel: function({....}), // modal footer cancel button callback
            shadow: boolean, //whether show shadow or not 
        })
    </code>
</pre>
