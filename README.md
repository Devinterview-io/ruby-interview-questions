<div data-v-5e9078c0=""><h1 data-v-5e9078c0="">Top 84 Ruby interview
    questions and answers in 2021.</h1> <p data-v-5e9078c0="">
      You can check all
      84
      Ruby interview questions here 👉
      https://devinterview.io/dev/ruby-interview-questions
    </p> <br data-v-5e9078c0=""> <div data-v-5e9078c0="" class="unit"><div><h2>🔹 1. Is there an equivalent of “continue” in Ruby?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>Yes, it's called <code>next</code>.</p><pre><code><span class="token cVar">for</span> i <span class="token cVar">in</span> <span class="token cNum">0.</span><span class="token cNum">.5</span>
   <span class="token cVar">if</span> i <span class="token cBase">&lt;</span> <span class="token cNum">2</span>
     next
   end
   puts <span class="token cString">"Value of local variable is #{i}"</span>
end</code></pre></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/4010039/equivalent-of-continue-in-ruby" rel="noreferrer" target="_blank" title="Is there an equivalent of “continue” in Ruby? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 2. Which core object includes the "Kernel" module?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p><code>Object</code></p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://raw.githubusercontent.com/undr/ruby-trivia/master/README.md" rel="noreferrer" target="_blank" title="Which core object includes the &quot;Kernel&quot; module?   Interview Questions Source To Answer">githubusercontent.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 3. What is an object?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>An instance of a class. To some, it's also the root class in ruby (Object). Classes themselves descend from the Object root class.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/4010039/equivalent-of-continue-in-ruby" rel="noreferrer" target="_blank" title="What is an object? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 4. What can you say about an identifier that begins with a capital letter?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>It is a constant.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://raw.githubusercontent.com/undr/ruby-trivia/master/README.md" rel="noreferrer" target="_blank" title="What can you say about an identifier that begins with a capital letter?   Interview Questions Source To Answer">githubusercontent.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 5. What are rubygems?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p><strong>rubygems</strong> is package manager software for ruby libraries (i.e. gems). The package manager has basic CRUD operations, dependency trees, and supports asynchronous communication between multiple gem servers.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/4010039/equivalent-of-continue-in-ruby" rel="noreferrer" target="_blank" title="What are rubygems? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 6. What is a class?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>Classes hold <strong>data</strong>, have <strong>methods</strong> that interact with that data, and are used to <strong>instantiate objects</strong>.</p><pre><code><span class="token cVar">class</span> <span class="token class-name">WhatAreClasses</span>
  <span class="token cVar">def</span> <span class="token method-definition"><span class="token cMod">initialize</span></span>
    <span class="token cVar">@data</span> <span class="token cBase">=</span> <span class="token cString">"I'm instance data of this object. Hello."</span>
  <span class="token cVar">end</span>

  <span class="token cVar">def</span> <span class="token method-definition"><span class="token cMod">method</span></span>
    puts <span class="token cVar">@data</span><span class="token cBase">.</span>gsub<span class="token cBase">(</span><span class="token cString">"instance"</span><span class="token cBase">,</span> <span class="token cString">"altered"</span><span class="token cBase">)</span>
  <span class="token cVar">end</span>
<span class="token cVar">end</span>

object <span class="token cBase">=</span> <span class="token cMod">WhatAreClasses</span><span class="token cBase">.</span><span class="token cVar">new</span>
<span class="token class-name">object<span class="token cBase">.</span>method</span>
 <span class="token cComment">#=&gt; I'm altered data of this object. Hello.</span></code></pre></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/4010039/equivalent-of-continue-in-ruby" rel="noreferrer" target="_blank" title="What is a class? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 7. What is the highest level in the object model?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p><code>BasicObject</code></p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://raw.githubusercontent.com/undr/ruby-trivia/master/README.md" rel="noreferrer" target="_blank" title="What is the highest level in the object model? Interview Questions Source To Answer">githubusercontent.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 8. Is everything in Ruby an object?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>Methods are not objects. Blocks are not objects. Keywords are not objects. However, there exist Method objects and Proc objects, and some keywords refer to objects.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://raw.githubusercontent.com/undr/ruby-trivia/master/README.md" rel="noreferrer" target="_blank" title="Is everything in Ruby an object?   Interview Questions Source To Answer">githubusercontent.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 9. Why Ruby is known as a language of flexibility?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>Ruby is known as a language of flexibility because it facilitates its author to alter the programming elements. Some specific parts of the language can be removed or redefined. Ruby does not restrict the user. For example, to add two numbers, Ruby allows to use <code>+</code> sign or the word <code>plus</code>. This alteration can be done with Ruby's built-in class Numeric.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://www.javatpoint.com/ruby-interview-questions" rel="noreferrer" target="_blank" title="Why Ruby is known as a language of flexibility? Interview Questions Source To Answer">javatpoint.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 10. How might you specify a default value for a hash?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>Pass the default values as arguments to <code>::new</code> on initialization or change the default directly with the method <code>Hash#default</code>. You may also provide a default at the time of query with <code>Hash#fetch</code>.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://raw.githubusercontent.com/undr/ruby-trivia/master/README.md" rel="noreferrer" target="_blank" title="How might you specify a default value for a hash?  Interview Questions Source To Answer">githubusercontent.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 11. Explain some differences between Ruby and Python</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>Similarities:</p><ul><li>High level language</li><li>Support multiple platforms</li><li>Use interactive prompt called irb</li><li>Server side scripting language</li></ul><p>Differences:</p><ul><li>Ruby is fully object oriented while Python is not.</li><li>Ruby supports EclipseIDE while Python supports multiple IDEs.</li><li>Ruby use Mixins while Python doesn't.</li><li>Ruby supports blocks, procs and lambdas while Python doesn't.</li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://www.javatpoint.com/ruby-interview-questions" rel="noreferrer" target="_blank" title="Explain some differences between Ruby and Python Interview Questions Source To Answer">javatpoint.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 12. Are instance methods public or private?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>They are public by default. You can change their visibility using <code>Module#private</code>, <code>Module#protected</code>, or back again using <code>Module#public</code>.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://raw.githubusercontent.com/undr/ruby-trivia/master/README.md" rel="noreferrer" target="_blank" title="Are instance methods public or private?   Interview Questions Source To Answer">githubusercontent.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 13. Are class variables inherited?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>No. The behavior is different than inheritance. Any alteration of a class variable by a subclass affects that class variable in the superclass and all other subclasses of the superclass.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://raw.githubusercontent.com/undr/ruby-trivia/master/README.md" rel="noreferrer" target="_blank" title="Are class variables inherited?   Interview Questions Source To Answer">githubusercontent.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 14. Can you call a private method outside a Ruby class using its object?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>Yes, with the help of the <code>send</code> method.</p><p>Given the class <code>Test</code>:</p><pre><code><span class="token cVar">class</span> <span class="token class-name">Test</span>
   <span class="token cVar">private</span>
       <span class="token cVar">def</span> <span class="token method-definition"><span class="token cMod">method</span></span>
         p <span class="token cString">"I am a private method"</span>
      <span class="token cVar">end</span>
<span class="token cVar">end</span></code></pre><p>We can execute the private method using <code>send</code>:</p><pre><code><span class="token cBase">&gt;</span><span class="token cBase">&gt;</span> <span class="token cMod">Test</span><span class="token cBase">.</span><span class="token cVar">new</span><span class="token cBase">.</span>send<span class="token cBase">(</span><span class="token symbol">:method</span><span class="token cBase">)</span>
<span class="token cString">"I am a private method"</span></code></pre></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://www.toptal.com/ruby/interview-questions" rel="noreferrer" target="_blank" title="Can you call a private method outside a Ruby class using its object? Interview Questions Source To Answer">toptal.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div><div data-v-5e9078c0="" class="unit"><div><h2>🔹 15. There are three ways to invoke a method in ruby. Can you give me at least two?</h2></div> <div><h3>Answer:</h3> <div class="answer"><div><div><div class="AnswerBody"><p>We are looking for the <strong>dot operator</strong> (or period operator), the <strong>Object#send</strong> method, or <strong>method(:foo).call</strong></p><pre><code>object <span class="token cBase">=</span> <span class="token builtin">Object</span><span class="token cBase">.</span><span class="token cVar">new</span>
<span class="token class-name">puts</span> object<span class="token cBase">.</span>object_id
 <span class="token cComment">#=&gt; 282660</span>

puts object<span class="token cBase">.</span>send<span class="token cBase">(</span><span class="token symbol">:object_id</span><span class="token cBase">)</span>
 <span class="token cComment">#=&gt; 282660</span>

puts object<span class="token cBase">.</span>method<span class="token cBase">(</span><span class="token symbol">:object_id</span><span class="token cBase">)</span><span class="token cBase">.</span>call <span class="token cComment"># (Kudos to Ezra)</span>
 <span class="token cComment">#=&gt; 282660</span></code></pre></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://gist.github.com/ryansobol/5252653#file-gistfile1-md" rel="noreferrer" target="_blank" title="There are three ways to invoke a method in ruby.  Can you give me at least two? Interview Questions Source To Answer">gist.github.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br><br></div> <div data-v-5e9078c0="" class="end"></div> <br data-v-5e9078c0="">
    Thanks 🙌 for reading and good luck on your next tech interview!
    <br data-v-5e9078c0="">
    Explore 3800+ dev interview question here 👉
    <a data-v-5e9078c0="" href="https://devinterview.io/">Devinterview.io</a></div>
