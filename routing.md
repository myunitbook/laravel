# Default Router

<pre>
Router::get('/',function(){
  return view('welcome');
});
</pre>

# Page Router

<pre>
Router::get('/hello',function(){
  return 'welcome to laravel';
});
</pre>
