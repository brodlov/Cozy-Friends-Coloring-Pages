# Cozy-Friends-Coloring-Pages
Print Cozy Friend PDF coloring pages for kids. The drawings are of cute friends in the Cozy Friend coloring book, uniquely illustrated by CoCoWyo. This 'Cozy Friends Coloring Book' includes: 40 hand-drawn pages ready for coloring. Super cute coloring pages for stress relief and relaxation. Single-sided, Discover best ideas and inspiration


<style type="text/css">

#toc {

    width: 99%;

    margin: 5px auto;

}

.postname {

    font-weight: 10px;

    font-size: 10px;

    background: #fff;

    margin-left: -10px; 

    padding-left: 20px; 

    list-style-type: none;

}

.postname li {

    border-bottom: #ddd 1px dotted;

    margin-right: 5px;

    padding: 5px 0;

}

</style>

<h1>Best Sellers:</h1>

<div id="toc">

    <div class="postname" id="recent-posts"></div>

</div>

<script type="text/javascript">

  var blogFeed = 'https://newyorkmnetwork.blogspot.com/feeds/posts/default?alt=json-in-script&max-results=9925'; 

  function loadtoc(json) {

    var posts = json.feed.entry;

    var output = '<ul>';

    for (var i = 0; i < posts.length; i++) {

      var post = posts[i];

      var title = post.title.$t;

      var link = post.link.find(function(l) { return l.rel == 'alternate'; }).href;

      output += '<li><a href="' + link + '">' + title + '</a></li>';

    }

    output += '</ul>';

    document.getElementById('recent-posts').innerHTML = output;

  }

  var script = document.createElement('script');

  script.src = blogFeed + '&callback=loadtoc';

  document.getElementsByTagName('head')[0].appendChild(script);

</script>
