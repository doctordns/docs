### ASP.NET MVC now escapes spaces in strings passed in via route parameters

|   |   |
|---|---|
|Details|In order to conform to RFC 2396, spaces in route paths are now escaped when populating action parameters from a route. So, whereas  <code>/controller/action/some data</code> would previously match the route <code>/controller/action/{data}</code> and provide <code>some data</code> as the data parameter, it will now provide <code>some%20data</code> instead.|
|Suggestion|Code should be updated to unescape string parameters from a route. If the original URI is needed, it can be accessed with the <xref:System.Net.HttpWebRequest.RequestUri>.OriginalString API.|
|Scope|Minor|
|Version|4.5.2|
|Type|Runtime|
<<<<<<< HEAD
|Affected APIs|<ul><li>[System.Web.Http.RouteAttribute.#ctor(System.String)](https://msdn.microsoft.com/library/system.web.http.routeattribute(v=vs.118).aspx)</li></ul>|
|Analyzers|<ul><li>CD0125</li></ul>|
=======
|Affected APIs|<ul><li><xref:System.Web.Mvc.RouteAttribute.%23ctor(System.String)?displayProperty=nameWithType></li></ul>|
>>>>>>> upstream/master

