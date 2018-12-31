+++
title = "Contact"
date = "2016-03-20"
keywords = ["contact", "social", "links", "telephone", "email"]
#banner = "img/banners/banner-2.jpg"
draft = false
+++

<script>
    sessionStorage.redirect = location.href;
</script>
<meta http-equiv="refresh" content="0;URL='/about'">

<script>
(function(){
    var redirect = sessionStorage.redirect;
    delete sessionStorage.redirect;
    if (redirect && redirect != location.href) {
        history.replaceState(null, null, redirect);
    }
})();
</script>
