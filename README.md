# JavaScript---Coding-Challenge

var fs =require ('fs');const jsonToHtml = require(jsonToHtml);let Template = {<>:'div','html':'$(id),$(userName),$(video_name),$(action)};let data=[    {      "id": 1,      "username": "Gonzales",      "video_name": "The Ledergberg Replica Plating Experiment",      "action": "Downloaded"    },    {      "id": 2,      "username": "Dominique",      "video_name": "Atomic Structure of DNA",      "action": "Viewed"    },    {        "id": 2,        "username": "Mark",        "video_name": "Book of Chemistry",        "action": "Downloaded"    }]let button="Generated"let finalHtmlFile=jsonTOHtml.render(data,template)
console.log(finalHtmlFile)fs.writeFile('jsonToHtml)'.finalHtmlFile,function(err){console.log("Html File is Created")}
