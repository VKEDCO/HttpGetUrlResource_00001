1) HttpGetURLSource.rar contains an Android application that
gets the source of a URI with org.apache.http.client.HttpClient
using HTTP GET as implemented in org.apache.http.client.methods.HttpGet.
The URI is supplied by the user through a GUI. The HttpGetURLSourceAct
activity runs several trials to get the source code of the URL specified
by the URI.

2) HttpGetURLSource2.rar contains an Android application 
that retrieves the URL source via http. The application 
illustrates how the Application class can be extended and 
used to share information between activities in the same 
application. In this case application, HttpURLSource2Act
retrieves the source of a user-supplied URL and saves
it in a String member variable of HttpGetApp, which
extends Application. The second activity of this application,
DisplayURLSource, retrieves the url source from the
member variable and displays it in an EditText.

