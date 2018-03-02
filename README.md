# TEMPLATES

__Instead of looking them up for every project, they're at my fingertips.__

Steps to create a new project using this, thanks to [this blog post](http://www.tilcode.com/fork-your-own-repo-on-github/).

1. Create a new repo on GitHub. Do NOT initialize with a `README`.

2. Clone the new repo locally. This will give you a warning about having cloned an empty repository. That's okay, just ignore that.
<pre>   git clone &lt;new-repo&gt;</pre>

3. Add an Upstream remote (to Templates repo). Make sure you're in your repo directory
<pre>   git remote add upstream https://github.com/shamicker/templates.git</pre>

4. Pull from Templates repo.
<pre>   git pull upstream master</pre>

5. Push to the new repo.
<pre>   git push origin master</pre>

You're done! You'll have a leftover `upstream` remote. To remove it:
<pre>   git remote rm upstream</pre>
