newview-tool
============

Resubmit this with:

$.ajax({url: "/api/tools", type: "POST", data: {name: "newview", type: "view", gitUrl: "https://github.com/scraperwiki/newview-tool.git", public: true}}).complete(function(r){ console.log(r.responseText) })
