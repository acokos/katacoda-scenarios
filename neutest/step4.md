REST Klasse erstellen


If the parent directories aren't already in the project, 'mkdir -p' will create them for you. 

`mkdir -p /root/devonfw/workspaces/main/root/devonfw/workspaces/main/myapplication`{{execute T1}}

Switch to the editor and click 'Copy to Editor'. 

'REST.java' will be created automatically inside the newly created folder.

<pre class="file" data-filename="devonfw/workspaces/main/root/devonfw/workspaces/main/myapplication/REST.java">
public class HelloWorld 
{
 
       public static void main (String[] args)
       {
             // Ausgabe Hello World!
             System.out.println(&#34;REST Entity&#34;);
       }
}
</pre>

Entity klasse build
