Bodhi Cloud API
===========

The Bodhi Cloud API is a set of secure APIs that are used to store your data.  To access the Bodhi Cloud API, you need to login with you user and password which is provided by Hot Schedules.  The API docs are available at this location: <a href="https://api.bodhi.space/apidocs/index.html">https://api.bodhi.space/apidocs/index.html</a>.  If you enter your credentials (username and password) and click Explore, you will see a list of API which you can access for your namespace.  Depending on your access, you can try the APIs out within your namespace by clicking on each of the Types, Clicking GET/PUT/PATCH/DELETE finding a Try It Out Button and clicking on it.  NOTE: PUT/PATCH/DELETE operations perform actual changes to the type in your namespace

Each type has a set of GET, PUT, PATCH, DELETE api operations depending on the type.
* GET: performs a get operation on that type and will return back any data associated with that type.
* PUT: usually takes a parameter of the data the user want to put into that type and stores that desired data addition
* PATCH: usually takes a parameter of the data the user wants to patch for that type, there are examples suggested in the documentation
* Delete: warning: performing this operation will cause data loss and using this operation should be used with extreme caution.  Delete's the data from the type.
