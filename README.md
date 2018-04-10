# TEMPLATES

__Instead of looking them up for every project, they're at my fingertips.__

Steps to create a new project using this template, thanks to [this blog post](http://www.tilcode.com/fork-your-own-repo-on-github/).

1. Create a new repo on GitHub. Do NOT initialize with a `README`.

2. Clone this newly-created repo locally. This will give you a warning about having cloned an empty repository. That's okay, just ignore that.
<pre>   git clone &lt;new-repo&gt;</pre>

3. Make sure you're in the new repo directory (locally).
<pre> cd &lt;new-repo&gt;</pre>

4. Add an Upstream remote (to Templates repo).
<pre>   git remote add upstream https://github.com/shamicker/templates.git</pre>

5. Pull from Templates repo.
<pre>   git pull upstream master</pre>

6. Push to the new repo.
<pre>   git push origin master</pre>

7. You'll have a leftover `upstream` remote. To remove it:
<pre>   git remote rm upstream</pre>

You're done!
