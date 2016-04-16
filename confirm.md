---
layout: confirm
custom_css: sweetalert, index
custom_js: sweetalert
---
<script   src="https://code.jquery.com/jquery-2.2.3.min.js"   integrity="sha256-a23g1Nt4dtEYOj7bR+vTu7+T8VP13humZFBJNIYoEJo="   crossorigin="anonymous"></script>
<script>
$(document).ready(function() {
swal({ 
  title: "Thanks",
   text: "I'll get back to you ASAP",
    imageUrl: "/img/thumbs-up.jpg" 
  },
  function(){
    window.location.href = '/';
});
});
</script>