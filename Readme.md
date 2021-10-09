<H1>Hi this madhav</H1>
<P>ENJOY OUR New Backend Service to create your own little Socail Media App.<p>
<div class="postman-run-button"
data-postman-action="collection/import"
data-postman-var-1="fe20231cd363ee911317"></div>
<script type="text/javascript">
  (function (p,o,s,t,m,a,n) {
    !p[s] && (p[s] = function () { (p[t] || (p[t] = [])).push(arguments); });
    !o.getElementById(s+t) && o.getElementsByTagName("head")[0].appendChild((
      (n = o.createElement("script")),
      (n.id = s+t), (n.async = 1), (n.src = m), n
    ));
  }(window, document, "_pm", "PostmanRunObject", "https://run.pstmn.io/button.js"));
</script>
<p>Endpoints List</p>
<ul>
<li>/users      : to create new user</li>
<li>/users/{id} : to search user by id</li>
<li>/posts      : to create posts</li>
<li>/posts/users/{id}/{pages}:to query post of a particular user and return response by page no</li>
<li>/posts/{id} :to query post by post id</li>
</ul>

<h1>User Databse</h1>
<img src='./userDatabase.png'></img>

<h1>Post Database</h1>
<img src='./PostDatabase.png'></img>
