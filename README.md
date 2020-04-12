<p><strong>React</strong>&nbsp;(also known as&nbsp;<strong>React.js</strong>&nbsp;or&nbsp;<strong>ReactJS</strong>) is a&nbsp;<a title="JavaScript library" href="https://en.wikipedia.org/wiki/JavaScript_library">JavaScript library</a>&nbsp;for building&nbsp;<a class="mw-redirect" title="User interfaces" href="https://en.wikipedia.org/wiki/User_interfaces">user interfaces</a>. It is maintained by&nbsp;<a title="Facebook" href="https://en.wikipedia.org/wiki/Facebook">Facebook</a>&nbsp;and a community of individual developers and companies.</p>
<p>React can be used as a base in the development of&nbsp;<a title="Single-page application" href="https://en.wikipedia.org/wiki/Single-page_application">single-page</a>&nbsp;or mobile applications. However, React is only concerned with rendering data to the&nbsp;<a title="Document Object Model" href="https://en.wikipedia.org/wiki/Document_Object_Model">DOM</a>, and so creating React applications usually requires the use of additional libraries for&nbsp;<a title="State management" href="https://en.wikipedia.org/wiki/State_management">state management</a>&nbsp;and routing.&nbsp;<a title="Redux (JavaScript library)" href="https://en.wikipedia.org/wiki/Redux_(JavaScript_library)">Redux</a>&nbsp;and React Router&nbsp;are respective examples of such libraries.</p>

</br>

<table class="infobox vevent">
<tbody>
<tr>
<th scope="row"><a class="mw-redirect" title="" href="https://en.wikipedia.org/wiki/Software_developer">Original author(s)</a></th>
<td>Jordan Walke</td>
</tr>
<tr>
<th scope="row"><a class="mw-redirect" title="Software developer" href="https://en.wikipedia.org/wiki/Software_developer">Developer(s)</a></th>
<td>Facebook and community</td>
</tr>
<tr>
<th scope="row">Initial release</th>
<td>May&nbsp;29, 2013<span class="noprint">; 6 years ago</span></td>
</tr>
<tr>
<th scope="row"><a title="Software release life cycle" href="https://en.wikipedia.org/wiki/Software_release_life_cycle">Stable release</a></th>
<td>
<div>16.13.1 / March&nbsp;19, 2020<span class="noprint">; 21 days ago</span></div>
</td>
</tr>
<tr>
<th scope="row"><a title="Repository (version control)" href="https://en.wikipedia.org/wiki/Repository_(version_control)">Repository</a></th>
<td><span class="url"><a class="external text" href="https://github.com/facebook/react" rel="nofollow">React Repository</a></span></td>
</tr>
<tr>
<th scope="row">Written in</th>
<td><a title="JavaScript" href="https://en.wikipedia.org/wiki/JavaScript">JavaScript</a></td>
</tr>
<tr>
<th scope="row"><a title="Computing platform" href="https://en.wikipedia.org/wiki/Computing_platform">Platform</a></th>
<td><a title="Web platform" href="https://en.wikipedia.org/wiki/Web_platform">Web platform</a></td>
</tr>
<tr>
<th scope="row"><a title="Software categories" href="https://en.wikipedia.org/wiki/Software_categories#Categorization_approaches">Type</a></th>
<td><a title="JavaScript library" href="https://en.wikipedia.org/wiki/JavaScript_library">JavaScript library</a></td>
</tr>
<tr>
<th scope="row"><a title="Software license" href="https://en.wikipedia.org/wiki/Software_license">License</a></th>
<td><a title="MIT License" href="https://en.wikipedia.org/wiki/MIT_License">MIT License</a></td>
</tr>
<tr>
<th scope="row">Website</th>
<td><span class="url"><a class="external text" href="http://reactjs.org/" rel="nofollow">reactjs<wbr />.org</a></span></td>
</tr>
</tbody>
</table>
</br>

<div class="toctitle" dir="ltr" lang="en">
<h2 id="mw-toc-heading">Contents</h2>
<label class="toctogglelabel" for="toctogglecheckbox"></label></div>
<ul>
<li class="toclevel-1 tocsection-1"><a href="#Basic_usage"><span class="toctext">Basic usage</span></a></li>
<li class="toclevel-1 tocsection-2"><a href="#Notable_features"><span class="toctext">Notable features</span></a>
<ul>
<li class="toclevel-2 tocsection-3"><a href="#Components"><span class="toctext">Components</span></a></li>
<li class="toclevel-2 tocsection-4"><a href="#Functional_components"><span class="toctext">Functional components</span></a></li>
<li class="toclevel-2 tocsection-5"><a href="#Class-based_components"><span class="toctext">Class-based components</span></a></li>
<li class="toclevel-2 tocsection-6"><a href="#Virtual_DOM"><span class="toctext">Virtual DOM</span></a></li>
<li class="toclevel-2 tocsection-7"><a href="#Lifecycle_methods"><span class="toctext">Lifecycle methods</span></a></li>
<li class="toclevel-2 tocsection-8"><a href="#JSX"><span class="toctext">JSX</span></a></li>
<li class="toclevel-2 tocsection-9"><a href="#Architecture_beyond_HTML"><span class="toctext">Architecture beyond HTML</span></a></li>
<li class="toclevel-2 tocsection-10"><a href="#React_Hooks"><span class="toctext">React Hooks</span></a>
<ul>
<li class="toclevel-3 tocsection-11"><a href="#Rules_of_Hooks"><span class="toctext">Rules of Hooks</span></a></li>
<li class="toclevel-3 tocsection-12"><a href="#Custom_Hooks"><span class="toctext">Custom Hooks</span></a></li>
</ul>
</li>
</ul>
</li>
<li class="toclevel-1 tocsection-13"><a href="#Common_idioms"><span class="toctext">Common idioms</span></a>
<ul>
<li class="toclevel-2 tocsection-14"><a href="#Use_of_the_Flux_architecture"><span class="toctext">Use of the Flux architecture</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-15"><a href="#Future_development"><span class="toctext">Future development</span></a></li>
<li class="toclevel-1 tocsection-16"><a href="#History"><span class="toctext">History</span></a>
<ul>
<li class="toclevel-2 tocsection-17"><a href="#Licensing"><span class="toctext">Licensing</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-18"><a href="#Books"><span class="toctext">Books</span></a></li>
</ul>

<h2><span id="Basic_usage" class="mw-headline">Basic usage</span></h2>
<p>The following is a rudimentary example of React usage in HTML with&nbsp;<a class="mw-redirect" title="React (JavaScript library)" href="https://en.wikipedia.org/wiki/React_(JavaScript_library)#JSX">JSX</a>&nbsp;and JavaScript.</p>
<div class="mw-highlight mw-highlight-lang-html mw-content-ltr" dir="ltr">
<pre><span class="p">&lt;</span><span class="nt">div</span> <span class="na">id</span><span class="o">=</span><span class="s">"myReactApp"</span><span class="p">&gt;&lt;/</span><span class="nt">div</span><span class="p">&gt;</span>

<span class="p">&lt;</span><span class="nt">script</span> <span class="na">type</span><span class="o">=</span><span class="s">"text/babel"</span><span class="p">&gt;</span>
  <span class="kd">function</span> <span class="nx">Greeter</span><span class="p">(</span><span class="nx">props</span><span class="p">)</span> <span class="p">{</span>
    <span class="k">return</span> <span class="o">&lt;</span><span class="nx">h1</span><span class="o">&gt;</span><span class="p">{</span><span class="nx">props</span><span class="p">.</span><span class="nx">greeting</span><span class="p">}</span><span class="o">&lt;</span><span class="err">/h1&gt;</span>
  <span class="p">}</span>
  <span class="kd">var</span> <span class="nx">App</span> <span class="o">=</span> <span class="o">&lt;</span><span class="nx">Greeter</span> <span class="nx">greeting</span><span class="o">=</span><span class="s2">"Hello World!"</span> <span class="o">/&gt;</span><span class="p">;</span>
  <span class="nx">ReactDOM</span><span class="p">.</span><span class="nx">render</span><span class="p">(</span><span class="nx">App</span><span class="p">,</span> <span class="nb">document</span><span class="p">.</span><span class="nx">getElementById</span><span class="p">(</span><span class="s1">'myReactApp'</span><span class="p">));</span>
<span class="p">&lt;/</span><span class="nt">script</span><span class="p">&gt;</span>
</pre>
</div>
<p>The&nbsp;<code>Greeter</code>&nbsp;function is a React component that accepts a property&nbsp;<code>greeting</code>. The variable&nbsp;<code>App</code>&nbsp;is an instance of the&nbsp;<code>Greeter</code>&nbsp;component where the&nbsp;<code>greeting</code>&nbsp;property is set to&nbsp;<code>'Hello World!'</code>. The&nbsp;<code>ReactDOM.render</code>&nbsp;method then renders our Greeter component inside the&nbsp;<a title="Document Object Model" href="https://en.wikipedia.org/wiki/Document_Object_Model">DOM</a>&nbsp;element with id&nbsp;<code>myReactApp</code>.</p>
<p>When displayed in a web browser the result will be</p>
<div class="mw-highlight mw-highlight-lang-html mw-content-ltr" dir="ltr">
<pre><span class="p">&lt;</span><span class="nt">div</span> <span class="na">id</span><span class="o">=</span><span class="s">"myReactApp"</span><span class="p">&gt;</span>
  <span class="p">&lt;</span><span class="nt">h1</span><span class="p">&gt;</span>Hello World!<span class="p">&lt;/</span><span class="nt">h1</span><span class="p">&gt;</span>
<span class="p">&lt;/</span><span class="nt">div</span><span class="p">&gt;</span>
</pre>
</div>
<h2><span id="Notable_features" class="mw-headline">Notable features</span></h2>
<h3><span id="Components" class="mw-headline">Components</span></h3>
<p>React code is made of entities called components. Components can be rendered to a particular element in the&nbsp;<a title="Document Object Model" href="https://en.wikipedia.org/wiki/Document_Object_Model">DOM</a>&nbsp;using the React DOM library. When rendering a component, one can pass in values that are known as "props":</p>
<div class="mw-highlight mw-highlight-lang-js mw-content-ltr" dir="ltr">
<pre><span class="nx">ReactDOM</span><span class="p">.</span><span class="nx">render</span><span class="p">(</span><span class="o">&lt;</span><span class="nx">Greeter</span> <span class="nx">greeting</span><span class="o">=</span><span class="s2">"Hello World!"</span> <span class="o">/&gt;</span><span class="p">,</span> <span class="nb">document</span><span class="p">.</span><span class="nx">getElementById</span><span class="p">(</span><span class="s1">'myReactApp'</span><span class="p">));</span>
</pre>
</div>
<p>The two primary ways of declaring components in React is via functional components and class-based components.</p>
<h3><span id="Functional_components" class="mw-headline">Functional components</span></h3>
<p>Functional components are declared with a function that then returns some JSX.</p>
<div class="mw-highlight mw-highlight-lang-js mw-content-ltr" dir="ltr">
<pre><span class="kr">const</span> <span class="nx">Greeting</span> <span class="o">=</span> <span class="p">(</span><span class="nx">props</span><span class="p">)</span> <span class="p">=&gt;</span> <span class="o">&lt;</span><span class="nx">div</span><span class="o">&gt;</span><span class="nx">Hello</span><span class="p">,</span> <span class="p">{</span><span class="nx">props</span><span class="p">.</span><span class="nx">name</span><span class="p">}</span><span class="o">!&lt;</span><span class="err">/div&gt;;</span>
</pre>
</div>
<h3><span id="Class-based_components" class="mw-headline">Class-based components</span></h3>
<p>Class-based components are declared using&nbsp;<a title="ECMAScript" href="https://en.wikipedia.org/wiki/ECMAScript">ES6</a>&nbsp;classes. They are also known as "stateful" components, because their state can hold values throughout the component and can be passed to child components through props:</p>
<div class="mw-highlight mw-highlight-lang-js mw-content-ltr" dir="ltr">
<pre><span class="kr">class</span> <span class="nx">ParentComponent</span> <span class="kr">extends</span> <span class="nx">React</span><span class="p">.</span><span class="nx">Component</span> <span class="p">{</span>
  <span class="nx">state</span> <span class="o">=</span> <span class="p">{</span> <span class="nx">color</span><span class="o">:</span> <span class="s1">'green'</span> <span class="p">};</span>
  <span class="nx">render</span><span class="p">()</span> <span class="p">{</span>
    <span class="k">return</span> <span class="p">(</span>
      <span class="o">&lt;</span><span class="nx">ChildComponent</span> <span class="nx">color</span><span class="o">=</span><span class="p">{</span><span class="k">this</span><span class="p">.</span><span class="nx">state</span><span class="p">.</span><span class="nx">color</span><span class="p">}</span> <span class="o">/&gt;</span>
    <span class="p">);</span>
  <span class="p">}</span>
<span class="p">}</span>
</pre>
</div>
<h3><span id="Virtual_DOM" class="mw-headline">Virtual DOM</span></h3>
<p>Another notable feature is the use of a virtual&nbsp;<a title="Document Object Model" href="https://en.wikipedia.org/wiki/Document_Object_Model">Document Object Model</a>, or virtual DOM. React creates an&nbsp;<a title="In-memory processing" href="https://en.wikipedia.org/wiki/In-memory_processing">in-memory</a>&nbsp;data-structure cache, computes the resulting differences, and then updates the browser's displayed DOM efficiently.&nbsp;This allows the programmer to write code as if the entire page is rendered on each change, while the React libraries only render subcomponents that actually change.</p>
<h3><span id="Lifecycle_methods" class="mw-headline">Lifecycle methods</span></h3>
<p>Lifecycle methods are&nbsp;<a title="Hooking" href="https://en.wikipedia.org/wiki/Hooking">hooks</a>&nbsp;that allow execution of code at set points during a component's lifetime.</p>
<ul>
<li><code>shouldComponentUpdate</code>&nbsp;allows the developer to prevent unnecessary re-rendering of a component by returning false if a render is not required.</li>
<li><code>componentDidMount</code>&nbsp;is called once the component has "mounted" (the component has been created in the user interface, often by associating it with a&nbsp;<a title="Document Object Model" href="https://en.wikipedia.org/wiki/Document_Object_Model">DOM</a>&nbsp;node). This is commonly used to trigger data loading from a remote source via an&nbsp;<a class="mw-redirect" title="API" href="https://en.wikipedia.org/wiki/API">API</a>.</li>
<li><code>componentWillUnmount</code>&nbsp;is called immediately before the component is torn down or "unmounted". This is commonly used to clear resource demanding dependencies to the component that will not simply be removed with the unmounting of the component (e.g., removing any&nbsp;<code>setInterval()</code>&nbsp;instances that are related to the component, or an "<a title="Event (computing)" href="https://en.wikipedia.org/wiki/Event_(computing)">eventListener</a>" set on the "document" because of the presence of the component)</li>
<li><code>render</code>&nbsp;is the most important lifecycle method and the only required one in any component. It is usually called every time the component's state is updated, which should be reflected in the user interface.</li>
</ul>
<h3><span id="JSX" class="mw-headline">JSX</span></h3>
<p>JSX, or JavaScript&nbsp;<a title="XML" href="https://en.wikipedia.org/wiki/XML">XML</a>&nbsp;, is an extension to the JavaScript language syntax.&nbsp;Similar in appearance to HTML, JSX provides a way to structure component rendering using syntax familiar to many developers. React components are typically written using JSX, although they do not have to be (components may also be written in pure JavaScript). JSX is similar to another extension syntax created by Facebook for&nbsp;<a title="PHP" href="https://en.wikipedia.org/wiki/PHP">PHP</a>&nbsp;called&nbsp;<a title="XHP" href="https://en.wikipedia.org/wiki/XHP">XHP</a>.</p>
<p>An example of JSX code:</p>
<div class="mw-highlight mw-highlight-lang-js mw-content-ltr" dir="ltr">
<pre><span class="lineno"> 1 </span><span class="kr">class</span> <span class="nx">App</span> <span class="kr">extends</span> <span class="nx">React</span><span class="p">.</span><span class="nx">Component</span> <span class="p">{</span>
<span class="lineno"> 2 </span>  <span class="nx">render</span><span class="p">()</span> <span class="p">{</span>
<span class="lineno"> 3 </span>    <span class="k">return</span> <span class="p">(</span>
<span class="lineno"> 4 </span>      <span class="o">&lt;</span><span class="nx">div</span><span class="o">&gt;</span>
<span class="lineno"> 5 </span>        <span class="o">&lt;</span><span class="nx">p</span><span class="o">&gt;</span><span class="nx">Header</span><span class="o">&lt;</span><span class="err">/p&gt;</span>
<span class="lineno"> 6 </span>        <span class="o">&lt;</span><span class="nx">p</span><span class="o">&gt;</span><span class="nx">Content</span><span class="o">&lt;</span><span class="err">/p&gt;</span>
<span class="lineno"> 7 </span>        <span class="o">&lt;</span><span class="nx">p</span><span class="o">&gt;</span><span class="nx">Footer</span><span class="o">&lt;</span><span class="err">/p&gt;</span>
<span class="lineno"> 8 </span>      <span class="o">&lt;</span><span class="err">/div&gt;</span>
<span class="lineno"> 9 </span>    <span class="p">);</span>
<span class="lineno">10 </span>  <span class="p">}</span>
<span class="lineno">11 </span><span class="p">}</span>
</pre>
</div>
<dl>
<dt>Nested elements</dt>
</dl>
<p>Multiple elements on the same level need to be wrapped in a single container element such as the&nbsp;<code>&lt;div&gt;</code>&nbsp;element shown above, or returned as an array.</p>
<dl>
<dt>Attributes</dt>
</dl>
<p>JSX provides a range of element attributes designed to mirror those provided by HTML. Custom attributes can also be passed to the component.&nbsp;All attributes will be received by the component as props.</p>
<dl>
<dt>JavaScript expressions</dt>
</dl>
<p>JavaScript&nbsp;<a title="Expression (computer science)" href="https://en.wikipedia.org/wiki/Expression_(computer_science)">expressions</a>&nbsp;(but not&nbsp;<a title="Statement (computer science)" href="https://en.wikipedia.org/wiki/Statement_(computer_science)">statements</a>) can be used inside JSX with curly brackets&nbsp;<code>{}</code>:</p>
<div class="mw-highlight mw-highlight-lang-js mw-content-ltr" dir="ltr">
<pre>  <span class="o">&lt;</span><span class="nx">h1</span><span class="o">&gt;</span><span class="p">{</span><span class="mi">10</span><span class="o">+</span><span class="mi">1</span><span class="p">}</span><span class="o">&lt;</span><span class="err">/h1&gt;</span>
</pre>
</div>
<p>The example above will render</p>
<div class="mw-highlight mw-highlight-lang-html mw-content-ltr" dir="ltr">
<pre>  <span class="p">&lt;</span><span class="nt">h1</span><span class="p">&gt;</span>11<span class="p">&lt;/</span><span class="nt">h1</span><span class="p">&gt;</span>
</pre>
</div>
<dl>
<dt>Conditional statements</dt>
</dl>
<p><a title="Conditional (computer programming)" href="https://en.wikipedia.org/wiki/Conditional_(computer_programming)">If&ndash;else statements</a>&nbsp;cannot be used inside JSX but conditional expressions can be used instead. The example below will render&nbsp;<code>{ i === 1&nbsp;? 'true'&nbsp;: 'false' }</code>&nbsp;as the string&nbsp;<code>'true'</code>&nbsp;because&nbsp;<code>i</code>&nbsp;is equal to 1.</p>
<div class="mw-highlight mw-highlight-lang-js mw-content-ltr" dir="ltr">
<pre><span class="lineno"> 1 </span><span class="kr">class</span> <span class="nx">App</span> <span class="kr">extends</span> <span class="nx">React</span><span class="p">.</span><span class="nx">Component</span> <span class="p">{</span>
<span class="lineno"> 2 </span>  <span class="nx">render</span><span class="p">()</span> <span class="p">{</span>
<span class="lineno"> 3 </span>    <span class="kr">const</span> <span class="nx">i</span> <span class="o">=</span> <span class="mi">1</span><span class="p">;</span>
<span class="lineno"> 4 </span>    <span class="k">return</span> <span class="p">(</span>
<span class="lineno"> 5 </span>      <span class="o">&lt;</span><span class="nx">div</span><span class="o">&gt;</span>
<span class="lineno"> 6 </span>        <span class="o">&lt;</span><span class="nx">h1</span><span class="o">&gt;</span><span class="p">{</span> <span class="nx">i</span> <span class="o">===</span> <span class="mi">1</span> <span class="o">?</span> <span class="s1">'true'</span> <span class="o">:</span> <span class="s1">'false'</span> <span class="p">}</span><span class="o">&lt;</span><span class="err">/h1&gt;</span>
<span class="lineno"> 7 </span>      <span class="o">&lt;</span><span class="err">/div&gt;</span>
<span class="lineno"> 8 </span>    <span class="p">);</span>
<span class="lineno"> 9 </span>  <span class="p">}</span>
<span class="lineno">10 </span><span class="p">}</span>
</pre>
</div>
<p>The above will render:</p>
<div class="mw-highlight mw-highlight-lang-html mw-content-ltr" dir="ltr">
<pre><span class="p">&lt;</span><span class="nt">div</span><span class="p">&gt;</span>
  <span class="p">&lt;</span><span class="nt">h1</span><span class="p">&gt;</span>true<span class="p">&lt;/</span><span class="nt">h1</span><span class="p">&gt;</span>
<span class="p">&lt;/</span><span class="nt">div</span><span class="p">&gt;</span>
</pre>
</div>
<p>Functions and JSX can be used in conditionals:</p>
<div class="mw-highlight mw-highlight-lang-js+genshitext mw-content-ltr" dir="ltr">
<pre><span class="lineno"> 1 </span><span class="kr">class</span> <span class="nx">App</span> <span class="kr">extends</span> <span class="nx">React</span><span class="p">.</span><span class="nx">Component</span> <span class="p">{</span>
<span class="lineno"> 2 </span>  <span class="nx">render</span><span class="p">()</span> <span class="p">{</span>
<span class="lineno"> 3 </span>    <span class="kr">const</span> <span class="nx">sections</span> <span class="o">=</span> <span class="p">[</span><span class="mi">1</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">];</span>
<span class="lineno"> 4 </span>    <span class="k">return</span> <span class="p">(</span>
<span class="lineno"> 5 </span>      <span class="o">&lt;</span><span class="nx">div</span><span class="o">&gt;</span>
<span class="lineno"> 6 </span>        <span class="p">{</span><span class="nx">sections</span><span class="p">.</span><span class="nx">length</span> <span class="o">&gt;</span> <span class="mi">0</span> <span class="o">&amp;&amp;</span> <span class="nx">sections</span><span class="p">.</span><span class="nx">map</span><span class="p">(</span><span class="nx">n</span> <span class="p">=&gt;</span> <span class="p">(</span>
<span class="lineno"> 7 </span>            <span class="cm">/* 'key' is used by react to keep track of list items and their changes */</span>
<span class="lineno"> 8 </span>            <span class="cm">/* Each 'key' must be unique */</span>
<span class="lineno"> 9 </span>            <span class="o">&lt;</span><span class="nx">div</span> <span class="nx">key</span><span class="o">=</span><span class="p">{</span><span class="s2">"section-"</span> <span class="o">+</span> <span class="nx">n</span><span class="p">}</span><span class="o">&gt;</span><span class="nx">Section</span> <span class="p">{</span><span class="nx">n</span><span class="p">}</span><span class="o">&lt;</span><span class="err">/div&gt;</span>
<span class="lineno">10 </span>        <span class="p">))}</span>
<span class="lineno">11 </span>      <span class="o">&lt;</span><span class="err">/div&gt;</span>
<span class="lineno">12 </span>    <span class="p">);</span>
<span class="lineno">13 </span>  <span class="p">}</span>
<span class="lineno">14 </span><span class="p">}</span>
</pre>
</div>
<p>The above will render:</p>
<div class="mw-highlight mw-highlight-lang-html mw-content-ltr" dir="ltr">
<pre><span class="p">&lt;</span><span class="nt">div</span><span class="p">&gt;</span>
  <span class="p">&lt;</span><span class="nt">div</span><span class="p">&gt;</span>Section 1<span class="p">&lt;/</span><span class="nt">div</span><span class="p">&gt;</span>
  <span class="p">&lt;</span><span class="nt">div</span><span class="p">&gt;</span>Section 2<span class="p">&lt;/</span><span class="nt">div</span><span class="p">&gt;</span>
  <span class="p">&lt;</span><span class="nt">div</span><span class="p">&gt;</span>Section 3<span class="p">&lt;/</span><span class="nt">div</span><span class="p">&gt;</span>
<span class="p">&lt;/</span><span class="nt">div</span><span class="p">&gt;</span>
</pre>
</div>
<p>Code written in JSX requires conversion with a tool such as&nbsp;<a class="mw-redirect" title="Babel (compiler)" href="https://en.wikipedia.org/wiki/Babel_(compiler)">Babel</a>&nbsp;before it can be understood by web browsers.&nbsp;This processing is generally performed during a&nbsp;<a title="Software build" href="https://en.wikipedia.org/wiki/Software_build">software build</a>&nbsp;process before the application is&nbsp;<a title="Software deployment" href="https://en.wikipedia.org/wiki/Software_deployment">deployed</a>.</p>
<h3><span id="Architecture_beyond_HTML" class="mw-headline">Architecture beyond HTML</span></h3>
<p>The basic architecture of React applies beyond rendering HTML in the browser. For example, Facebook has dynamic charts that render to&nbsp;<code>&lt;canvas&gt;</code>&nbsp;tags,&nbsp;and Netflix and&nbsp;<a title="PayPal" href="https://en.wikipedia.org/wiki/PayPal">PayPal</a>&nbsp;use universal loading to render identical HTML on both the server and client.</p>
<h3><span id="React_Hooks" class="mw-headline">React Hooks</span></h3>
<p>Hooks are functions that let developers "hook into" React state and lifecycle features from function components.&nbsp;They make codes readable and easily understandable. Hooks don&rsquo;t work inside classes &mdash; they let you use React without classes.</p>
<p>React provides a few built-in Hooks like&nbsp;<code>useState</code>,&nbsp;<code>useContext</code>,&nbsp;<code>useReducer</code>&nbsp;and&nbsp;<code>useEffect</code>&nbsp;to name a few. They are all stated in the Hooks API Reference.&nbsp;<code>useState</code>&nbsp;and&nbsp;<code>useEffect</code>, which are the most used, are for controlling states and side effects respectively in React Components.</p>
<h4><span id="Rules_of_Hooks" class="mw-headline">Rules of Hooks</span></h4>
<p>There are also rules of hooks&nbsp;which must be followed before they can be used.</p>
<ol>
<li>Hooks should only be called at the top level (not inside loops or if statements).</li>
<li>Hooks should only be called from React function components, not normal functions or class components</li>
</ol>
<h4><span id="Custom_Hooks" class="mw-headline">Custom Hooks</span></h4>
<p>Building your own hooks&nbsp;which are called custom hooks lets you extract component logic into reusable functions. A custom Hook is a JavaScript function whose name starts with &rdquo;use&rdquo; and that may call other Hooks. The rules of hooks also apply to them.</p>
<h2><span id="Common_idioms" class="mw-headline">Common idioms</span></h2>
<p>React does not attempt to provide a complete "application library". It is designed specifically for building user interfaces&nbsp;and therefore does not include many of the tools some developers might consider necessary to build an application. This allows the choice of whichever libraries the developer prefers to accomplish tasks such as performing network access or local data storage. Common patterns of usage have emerged as the library matures.</p>
<h3><span id="Use_of_the_Flux_architecture" class="mw-headline">Use of the Flux architecture</span></h3>
<p>To support React's concept of unidirectional data flow (which might be contrasted with&nbsp;<a title="AngularJS" href="https://en.wikipedia.org/wiki/AngularJS">AngularJS</a>'s bidirectional flow), the Flux architecture represents an alternative to the popular&nbsp;<a class="mw-redirect" title="Model-view-controller" href="https://en.wikipedia.org/wiki/Model-view-controller">model-view-controller</a>&nbsp;architecture. Flux features&nbsp;<em>actions</em>&nbsp;which are sent through a central&nbsp;<em>dispatcher</em>&nbsp;to a&nbsp;<em>store</em>, and changes to the store are propagated back to the view.&nbsp;When used with React, this propagation is accomplished through component properties.</p>
<p>Flux can be considered a variant of the&nbsp;<a title="Observer pattern" href="https://en.wikipedia.org/wiki/Observer_pattern">observer pattern</a>.</p>
<p>A React component under the Flux architecture should not directly modify any props passed to it, but should be passed callback functions that create&nbsp;<em>actions</em>&nbsp;which are sent by the dispatcher to modify the store. The action is an object whose responsibility is to describe what has taken place: for example, an action describing one user "following" another might contain a user id, a target user id, and the type&nbsp;<code>USER_FOLLOWED_ANOTHER_USER</code>.&nbsp;The stores, which can be thought of as models, can alter themselves in response to actions received from the dispatcher.</p>
<p>This pattern is sometimes expressed as "properties flow down, actions flow up". Many implementations of Flux have been created since its inception, perhaps the most well-known being&nbsp;<a title="Redux (JavaScript library)" href="https://en.wikipedia.org/wiki/Redux_(JavaScript_library)">Redux</a>, which features a single store, often called a&nbsp;<a title="Single source of truth" href="https://en.wikipedia.org/wiki/Single_source_of_truth">single source of truth</a>.</p>
<h2><span id="Future_development" class="mw-headline">Future development</span></h2>
<p>Project status can be tracked via the core team discussion forum.&nbsp;However, major changes to React go through the Future of React repository issues and&nbsp;<a class="mw-redirect" title="Pull request" href="https://en.wikipedia.org/wiki/Pull_request">pull requests</a>.&nbsp;This enables the React community to provide feedback on new potential features, experimental APIs and JavaScript syntax improvements.</p>
<h2><span id="History" class="mw-headline">History</span></h2>
<p>React was created by Jordan Walke, a software engineer at Facebook, who released an early prototype of React called "FaxJS".&nbsp;He was influenced by&nbsp;<a title="XHP" href="https://en.wikipedia.org/wiki/XHP">XHP</a>, an&nbsp;<a title="HTML" href="https://en.wikipedia.org/wiki/HTML">HTML</a>&nbsp;component library for&nbsp;<a title="PHP" href="https://en.wikipedia.org/wiki/PHP">PHP</a>. It was first deployed on Facebook's&nbsp;<a title="News Feed" href="https://en.wikipedia.org/wiki/News_Feed">News Feed</a>&nbsp;in 2011 and later on&nbsp;<a title="Instagram" href="https://en.wikipedia.org/wiki/Instagram">Instagram</a>&nbsp;in 2012.&nbsp;It was open-sourced at JSConf US in May 2013.</p>
<p><a title="React Native" href="https://en.wikipedia.org/wiki/React_Native">React Native</a>, which enables native&nbsp;<a title="Android (operating system)" href="https://en.wikipedia.org/wiki/Android_(operating_system)">Android</a>,&nbsp;<a title="IOS" href="https://en.wikipedia.org/wiki/IOS">iOS</a>, and&nbsp;<a title="Universal Windows Platform" href="https://en.wikipedia.org/wiki/Universal_Windows_Platform">UWP</a>&nbsp;development with React, was announced at Facebook's React Conf in February 2015 and open-sourced in March 2015.</p>
<p>On April 18, 2017, Facebook announced&nbsp;<a title="React Fiber" href="https://en.wikipedia.org/wiki/React_Fiber">React Fiber</a>, a new core algorithm of React library for building&nbsp;<a title="User interface" href="https://en.wikipedia.org/wiki/User_interface">user interfaces</a>.&nbsp;React Fiber was to become the foundation of any future improvements and feature development of the React library.</p>
<p>On September 26, 2017, React 16.0 was released to the public.</p>
<p>On February 16, 2019, React 16.8 was released to the public.&nbsp;The release introduced React Hooks.</p>
<table class="wikitable"><caption>Versions</caption>
<tbody>
<tr>
<th>Version</th>
<th>Release Date</th>
<th>Changes</th>
</tr>
<tr>
<td>0.3.0</td>
<td>29 May 2013</td>
<td>Initial Public Release</td>
</tr>
<tr>
<td>0.4.0</td>
<td>20 July 2013</td>
<td>Support for comment nodes &lt;div&gt;{/* */}&lt;/div&gt;, Improved server-side rendering APIs, Removed React.autoBind, Support for the key prop, Improvements to forms, Fixed bugs.</td>
</tr>
<tr>
<td>0.5.0</td>
<td>20 October 2013</td>
<td>Improve Memory usage, Support for Selection and Composition events, Support for getInitialState and getDefaultProps in mixins, Added React.version and React.isValidClass, Improved compatibility for Windows.</td>
</tr>
<tr>
<td>0.8.0</td>
<td>20 December 2013</td>
<td>Added support for rows &amp; cols, defer &amp; async, loop for &lt;audio&gt; &amp; &lt;video&gt;, autoCorrect attributes. Added onContextMenu events, Upgraded jstransform and esprima-fb tools, Upgraded browserify.</td>
</tr>
<tr>
<td>0.9.0</td>
<td>20 February 2014</td>
<td>Added support for crossOrigin, download and hrefLang, mediaGroup and muted, sandbox, seamless, and srcDoc, scope attributes, Added any, arrayOf, component, oneOfType, renderable, shape to React.PropTypes, Added support for onMouseOver and onMouseOut event, Added support for onLoad and onError on &lt;img&gt; elements.</td>
</tr>
<tr>
<td>0.10.0</td>
<td>21 March 2014</td>
<td>Added support for srcSet and textAnchor attributes, add update function for immutable data, Ensure all void elements don't insert a closing tag.</td>
</tr>
<tr>
<td>0.11.0</td>
<td>17 July 2014</td>
<td>Improved SVG support, Normalized e.view event, Update $apply command, Added support for namespaces, Added new transformWithDetails API, includes pre-built packages under dist/, MyComponent() now returns a descriptor, not an instance.</td>
</tr>
<tr>
<td>0.12.0</td>
<td>21 November 2014</td>
<td>Added new features Spread operator ({...}) introduced to deprecate this.transferPropsTo, Added support for acceptCharset, classID, manifest HTML attributes, React.addons.batchedUpdates added to API, @jsx React.DOM no longer required, Fixed issues with CSS Transitions.</td>
</tr>
<tr>
<td>0.13.0</td>
<td>10 March 2015</td>
<td>Deprecated patterns that warned in 0.12 no longer work, ref resolution order has changed, Removed properties this._pendingState and this._rootNodeID, Support ES6 classes, Added API React.findDOMNode(component), Support for iterators and immutable-js sequences, Added new features React.addons.createFragment, deprecated React.addons.classSet.</td>
</tr>
<tr>
<td>0.14.1</td>
<td>29 October 2015</td>
<td>Added support for srcLang, default, kind attributes, and color attribute, Ensured legacy .props access on DOM nodes, Fixed scryRenderedDOMComponentsWithClass, Added react-dom.js.</td>
</tr>
<tr>
<td>15.0.0</td>
<td>07 April 2016</td>
<td>Initial render now uses document.createElement instead of generating HTML, No more extra &lt;span&gt;s, Improved SVG support, ReactPerf.getLastMeasurements() is opaque, New deprecations introduced with a warning, Fixed multiple small memory leaks, React DOM now supports the cite and profile HTML attributes and cssFloat, gridRow and gridColumn CSS properties.</td>
</tr>
<tr>
<td>15.1.0</td>
<td>20 May 2016</td>
<td>Fix a batching bug, Ensure use of the latest object-assign, Fix regression, Remove use of merge utility, Renamed some modules.</td>
</tr>
<tr>
<td>15.2.0</td>
<td>01 July 2016</td>
<td>Include component stack information, Stop validating props at mount time, Add React.PropTypes.symbol, Add onLoad handling to &lt;link&gt; and onError handling to &lt;source&gt; element, Add isRunning() API, Fix performance regression.</td>
</tr>
<tr>
<td>15.3.0</td>
<td>30 July 2016</td>
<td>Add React.PureComponent, Fix issue with nested server rendering, Add xmlns, xmlnsXlink to support SVG attributes and referrerPolicy to HTML attributes, updates React Perf Add-on, Fixed issue with ref.</td>
</tr>
<tr>
<td>15.3.1</td>
<td>19 August 2016</td>
<td>Improve performance of development builds, Cleanup internal hooks, Upgrade fbjs, Improve startup time of React, Fix memory leak in server rendering, fix React Test Renderer, Change trackedTouchCount invariant into a console.error.</td>
</tr>
<tr>
<td>15.4.0</td>
<td>16 November 2016</td>
<td>React package and browser build no longer includes React DOM, Improved development performance, Fixed occasional test failures, update batchedUpdates API, React Perf, and ReactTestRenderer.create().</td>
</tr>
<tr>
<td>15.4.1</td>
<td>23 November 2016</td>
<td>Restructure variable assignment, Fixed event handling, Fixed compatibility of browser build with AMD environments.</td>
</tr>
<tr>
<td>15.4.2</td>
<td>06 January 2017</td>
<td>Fixed build issues, Added missing package dependencies, Improved error messages.</td>
</tr>
<tr>
<td>15.5.0</td>
<td>07 April 2017</td>
<td>Added react-dom/test-utils, Removed peerDependencies, Fixed issue with Closure Compiler, Added a deprecation warning for React.createClass and React.PropTypes, Fixed Chrome bug.</td>
</tr>
<tr>
<td>15.5.4</td>
<td>11 April 2017</td>
<td>Fix compatibility with Enzyme by exposing batchedUpdates on shallow renderer, Update version of prop-types, Fix react-addons-create-fragment package to include loose-envify transform.</td>
</tr>
<tr>
<td>15.6.0</td>
<td>13 June 2017</td>
<td>Add support for CSS variables in style attribute and Grid style properties, Fix AMD support for addons depending on react, Remove unnecessary dependency, Add a deprecation warning for React.createClass and React.DOM factory helpers.</td>
</tr>
<tr>
<td>16.0.0</td>
<td>26 September 2017</td>
<td>Improved error handling with introduction of "error boundaries", React DOM allows passing non-standard attributes, Minor changes to setState behavior, remove react-with-addons.js build, Add React.createClass as create-react-class, React.PropTypes as prop-types, React.DOM as react-dom-factories, changes to the behavior of scheduling and lifecycle methods.</td>
</tr>
<tr>
<td>16.1.0</td>
<td>9 November 2017</td>
<td>Discontinuing Bower Releases, Fix an accidental extra global variable in the UMD builds, Fix onMouseEnter and onMouseLeave firing, Fix &lt;textarea&gt; placeholder, Remove unused code, Add a missing package.json dependency, Add support for React DevTools.</td>
</tr>
<tr>
<td>16.3.0</td>
<td>29 March 2018</td>
<td>Add a new officially supported context API, Add new packagePrevent an infinite loop when attempting to render portals with SSR, Fix an issue with this.state, Fix an IE/Edge issue.</td>
</tr>
<tr>
<td>16.3.1</td>
<td>03 April 2018</td>
<td>Prefix private API, Fix performance regression and error handling bugs in development mode, Add peer dependency, Fix a false positive warning in IE11 when using Fragment.</td>
</tr>
<tr>
<td>16.3.2</td>
<td>16 April 2018</td>
<td>Fix an IE crash, Fix labels in User Timing measurements, Add a UMD build, Improve performance of unstable_observedBits API with nesting.</td>
</tr>
<tr>
<td>16.4.0</td>
<td>24 May 2018</td>
<td>Add support for Pointer Events specification, Add the ability to specify propTypes, Fix reading context, Fix the getDerivedStateFromProps() support, Fix a testInstance.parent crash, Add React.unstable_Profiler component for measuring performance, Change internal event names.</td>
</tr>
<tr>
<td>16.5.0</td>
<td>05 September 2018</td>
<td>Add support for React DevTools Profiler, Handle errors in more edge cases gracefully, Add react-dom/profiling, Add onAuxClick event for browsers, Add movementX and movementY fields to mouse events, Add tangentialPressure and twist fields to pointer event.</td>
</tr>
<tr>
<td>16.6.0</td>
<td>23 October 2018</td>
<td>Add support for contextType, Support priority levels, continuations, and wrapped callbacks, Improve the fallback mechanism, Fix gray overlay on iOS Safari, Add React.lazy() for code splitting components.</td>
</tr>
<tr>
<td>16.7.0</td>
<td>20 December 2018</td>
<td>Fix performance of React.lazy for lazily-loaded components, Clear fields on unmount to avoid memory leaks, Fix bug with SSR, Fix a performance regression.</td>
</tr>
<tr>
<td>16.8.0</td>
<td>06 February 2019</td>
<td>Add Hooks, Add ReactTestRenderer.act() and ReactTestUtils.act() for batching updates, Support synchronous thenables passed to React.lazy(), Improve useReducer Hook lazy initialization API.</td>
</tr>
<tr>
<td>16.8.6</td>
<td>27 March 2019</td>
<td>Fix an incorrect bailout in useReducer(), Fix iframe warnings in Safari DevTools, Warn if contextType is set to Context.Consumer instead of Context, Warn if contextType is set to invalid values.</td>
</tr>
<tr>
<td>16.9.0</td>
<td>9 August 2019</td>
<td>Add &lt;React.Profiler&gt; API for gathering performance measurements programmatically. Remove unstable_ConcurrentMode in favor of unstable_createRoot</td>
</tr>
<tr>
<td>16.10.0</td>
<td>27 September 2019</td>
<td>Fix edge case where a hook update wasn't being memoized. Fix heuristic for determining when to hydrate, so we don't incorrectly hydrate during an update. Clear additional fiber fields during unmount to save memory. Fix bug with required text fields in Firefox. Prefer Object.is instead of inline polyfill, when available. Fix bug when mixing Suspense and error handling.</td>
</tr>
<tr>
<td>16.10.1</td>
<td>28 September 2019</td>
<td>Fix regression in Next.js apps by allowing Suspense mismatch during hydration to silently proceed</td>
</tr>
<tr>
<td>16.10.2</td>
<td>3 October 2019</td>
<td>Fix regression in react-native-web by restoring order of arguments in event plugin extractors</td>
</tr>
<tr>
<td>16.11.0</td>
<td>22 October 2019</td>
<td>Fix mouseenter handlers from firing twice inside nested React containers. Remove unstable_createRoot and unstable_createSyncRoot experimental APIs. (These are available in the Experimental channel as createRoot and createSyncRoot.)</td>
</tr>
<tr>
<td>16.12.0</td>
<td>14 November 2019</td>
<td>React DOM - Fix passive effects (<code>useEffect</code>) not being fired in a multi-root app.
<p>React Is - Fix&nbsp;<code>lazy</code>&nbsp;and&nbsp;<code>memo</code>&nbsp;types considered elements instead of components</p>
</td>
</tr>
<tr>
<td>16.13.0</td>
<td>26 February 2020</td>
<td>Features added in React Concurrent mode.
<p>Fix regressions in React core library and React Dom.</p>
</td>
</tr>
</tbody>
</table>
<h3><span id="Licensing" class="mw-headline">Licensing</span></h3>
<p>The initial public release of React in May 2013 used the&nbsp;<a class="mw-redirect" title="Apache License 2.0" href="https://en.wikipedia.org/wiki/Apache_License_2.0">Apache License 2.0</a>. In October 2014, React 0.12.0 replaced this with the&nbsp;<a title="BSD licenses" href="https://en.wikipedia.org/wiki/BSD_licenses#3-clause">3-clause BSD license</a>&nbsp;and added a separate PATENTS text file that permits usage of any Facebook patents related to the software:</p>
<blockquote>
<p>The license granted hereunder will terminate, automatically and without notice, for anyone that makes any claim (including by filing any lawsuit, assertion or other action) alleging (a) direct, indirect, or contributory infringement or inducement to infringe any patent: (i) by Facebook or any of its subsidiaries or affiliates, whether or not such claim is related to the Software, (ii) by any party if such claim arises in whole or in part from any software, product or service of Facebook or any of its subsidiaries or affiliates, whether or not such claim is related to the Software, or (iii) by any party relating to the Software; or (b) that any right in any patent claim of Facebook is invalid or unenforceable.</p>
</blockquote>
<p>This unconventional clause caused some controversy and debate in the React user community, because it could be interpreted to empower Facebook to revoke the license in many scenarios, for example, if Facebook sues the licensee prompting them to take "other action" by publishing the action on a blog or elsewhere. Many expressed concerns that Facebook could unfairly exploit the termination clause or that integrating React into a product might complicate a startup company's future acquisition.</p>
<p>Based on community feedback, Facebook updated the patent grant in April 2015 to be less ambiguous and more permissive:</p>
<blockquote>
<p>The license granted hereunder will terminate, automatically and without notice, if you (or any of your subsidiaries, corporate affiliates or agents) initiate directly or indirectly, or take a direct financial interest in, any Patent Assertion: (i) against Facebook or any of its subsidiaries or corporate affiliates, (ii) against any party if such Patent Assertion arises in whole or in part from any software, technology, product or service of Facebook or any of its subsidiaries or corporate affiliates, or (iii) against any party relating to the Software. [...] A "Patent Assertion" is any lawsuit or other action alleging direct, indirect, or contributory infringement or inducement to infringe any patent, including a cross-claim or counterclaim.</p>
</blockquote>
<p>The&nbsp;<a class="mw-redirect" title="Apache Software Foundation" href="https://en.wikipedia.org/wiki/Apache_Software_Foundation">Apache Software Foundation</a>&nbsp;considered this licensing arrangement to be incompatible with its licensing policies, as it "passes along risk to downstream consumers of our software imbalanced in favor of the licensor, not the licensee, thereby violating our Apache legal policy of being a universal donor", and "are not a subset of those found in the [Apache License 2.0], and they cannot be sublicensed as [Apache License 2.0]".&nbsp;In August 2017, Facebook dismissed the Apache Foundation's downstream concerns and refused to reconsider their license.&nbsp;The following month,&nbsp;<a title="WordPress" href="https://en.wikipedia.org/wiki/WordPress">WordPress</a>&nbsp;decided to switch its Gutenberg and Calypso projects away from React.</p>
<p>On September 23, 2017, Facebook announced that the following week, it would re-license Flow,&nbsp;<a class="new" title="Jest (JavaScript library) (page does not exist)" href="https://en.wikipedia.org/w/index.php?title=Jest_(JavaScript_library)&amp;action=edit&amp;redlink=1">Jest</a>, React, and Immutable.js under a standard&nbsp;<a title="MIT License" href="https://en.wikipedia.org/wiki/MIT_License">MIT License</a>; the company stated that React was "the foundation of a broad ecosystem of open source software for the web", and that they did not want to "hold back forward progress for nontechnical reasons".</p>
<p>On September 26, 2017, React 16.0.0 was released with the MIT license.&nbsp;The MIT license change has also been backported to the 15.x release line with React 15.6.2.</p>


</br>
<h2 id= "Books">Books </h2>




<ul>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(1).pdf" style="text-decoration:none;">30 Days of React    </a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(2).pdf" style="text-decoration:none;">Mastering React</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(3).pdf" style="text-decoration:none;">Beginning React</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(4).pdf" style="text-decoration:none;">Getting Started with React Native</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(5).pdf" style="text-decoration:none;">Hacking with React</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(6).pdf" style="text-decoration:none;">Introduction to React</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(7).pdf" style="text-decoration:none;">Learning React Native</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(8).pdf" style="text-decoration:none;">Learning React</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(9).pdf" style="text-decoration:none;">Learning Web Development with React and Bootstrap</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(10).pdf" style="text-decoration:none;">Mastering Full-Stack React Web Development</a></li>
	  <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(11).pdf" style="text-decoration:none;"> Practical React Native</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(12).pdf" style="text-decoration:none;">Pro MERN Stack: Full Stack Web App Development with Mongo, Express, React, and Node</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(13).pdf" style="text-decoration:none;">Pro React</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(14).pdf" style="text-decoration:none;">Progressive Web Apps with React</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(15).pdf" style="text-decoration:none;">Pure React</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(16).pdf" style="text-decoration:none;">React 16 Essentials</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(17).pdf" style="text-decoration:none;">React and React Native</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(18).pdf" style="text-decoration:none;">React Design Patterns and Best Practices</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(19).pdf" style="text-decoration:none;">React in Action</a></li>
                <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(20).pdf" style="text-decoration:none;">React Native Cookbook</a></li>	
	
 <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(21).pdf" style="text-decoration:none;">React Native for iOS Development</a></li>
	
<li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(22).pdf" style="text-decoration:none;">React Quickly</a></li>
  <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(23).pdf" style="text-decoration:none;">React Router Quick Start Guide</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(24).pdf" style="text-decoration:none;">React: Up and Running</a></li>	
	
 <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(25).pdf" style="text-decoration:none;">React Native Tutorial</a></li>
	
	
 <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(26).pdf" style="text-decoration:none;">ReactJS by Example - Building Modern Web Applications with React</a></li>
	
<li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(27).pdf" style="text-decoration:none;">ReactJS: Become a professional in web app development</a></li>
  <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(28).pdf" style="text-decoration:none;">ReactJS by Example - Building Modern Web Applications with React</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(29).pdf" style="text-decoration:none;">React JS Notes for Professionals</a></li>	
	
 <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(30).pdf" style="text-decoration:none;">The Road to learn React</a></li>
	
 <li><a target="_blank" href="https://github.com/manjunath5496/React-Books/blob/master/rct(31).pdf" style="text-decoration:none;">React 16 Essentials </a></li>
	

	
	
</ul>
