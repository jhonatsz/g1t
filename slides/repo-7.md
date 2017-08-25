### Exercise #1
<p style="font-size:25px;text-align:left;"> 4. Make changes in the file system</p>
<pre>
<code>
echo "foo foo bar bar" > file2.txt
git status
git diff
</code>
</pre>
<p style="font-size:25px;text-align:left;"> 5. Reset only non-staged to the clean state(latest commit) </p>
<pre>
<code>
git checkout .
</code>
</pre>
<p style="font-size:25px;text-align:left;"> 6. To reset working tree and index </p>
<pre>
<code>
git reset -- HEAD
</code>
</pre>
