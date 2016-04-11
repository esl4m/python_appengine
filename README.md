# python_appengine
hello world static webpage in app engine..

# To run the application server locally 
<code>dev_appserver.py python_appengine/hello_world/</code>

# To Deploy application on Google cloud platform (Google console)
Change the "helloworld" in hello_world/app.yaml 
<code>application: helloworld</code>
with your console application_id
then deploy
<code>appcfg.py update google_appengine/hello_world</code>
