---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Welcome! This is the website of our bi-weekly journal club on machine learning, from a mathematics and physics research perspective.
If you are interested in joining, please have a look [here]({{ site.baseurl }}{% link about.md %})!
<div id="next-meeting" style="background-color: #e7f3fe;
  border-left: 6px solid #2a7ae2; padding: 0pt 5pt; margin-bottom: 5pt"></div>

<script>
var next = new Date("2022-09-29T08:00:00+00:00")
var today = new Date();
while (next < today) { next.setTime(next.getTime() + 14*24*60*60*1000); };
document.getElementById("next-meeting").innerHTML = `The next meeting will be ${next}.`;
</script>
