### Exercise #3

<p style="font-size:25px;text-align:left;"> 1. Make a fast-forward merge</p>
<pre>
<code>
git checkout master
git merge branch-1
</code>
</pre>

<p style="font-size:25px;text-align:left;"> 2. Undo fast-forward merge</p>
<pre>
<code>
git reset --hard HEAD~1
</code>
</pre>

<p style="font-size:25px;text-align:left;"> 3. Make commit on master</p>
<pre>
<code>
echo "a very unimportant message" > file2.txt
git add file2.txt
git commit -m "m1"
</code>
</pre>
