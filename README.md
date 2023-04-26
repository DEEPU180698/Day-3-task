DAY 3 TASK

1.Iterate JSON for all for loops

// let data = [{
//     name:"Deepu H",
//     mail:"deepu@titan.co.in",
//     mobile:[9629301413],
//     country:"india",
// },
// {
//     name:"Ashok H",
// mail:"deepu@titan.co.in",
// mobile:[7812855356],
// country:"india",

//}]
// for loop
// for(let i=0;i<data.length;i++){
//     let obj=data[i];
//     console.log(obj.name);
//     console.log(obj.mobile);
// }
//for in
// for( let i in data){
//     console.log(data[i].name);
// }
// for Each
// data.forEach(function(obj){
//     console.log(obj.name);
// })

 // let text = "";
// for (let i of json[key].id) {
//  text += i; 
// }
//  console.log(text);

2.Resume in JSON format

//  let Resume={
//     name:"Deepu H",
//     age:25,
//     Email:"deepu@titan.co.in",
//     mobile:[7812855356,9629301413],
//     address:{
//         no:27,
//         street:"rajaji nagar,dinnur",
//         city:"hosur",
//         district:"krishnagiri",
//         state:"tamilnadu",
//         country:"india",
//     },
//     qualification:"diploma in mechanical engineering",
//     collage:"sankar polytechnic collage",
//     company:"titan",
//     experience:"4years",
//     position:"quality engineer",
//     langauges_known:["tamil","english","malayalam"],
//  }
//  console.log(Resume)

3.Difference between window, screen and document in Javascript

Window
Each browser tab has its own top-level window object. Each element has its own window object too.
nested within a parent window. each of these windows gets its own separate global object.
window always refers to window, but window parent and window top might refer to enclosing windows, giving access to other execution contexts.
Screen
The window object also has a screen object with properties describing the physical display.
Screen properties width and height are the full screen
screen properties availwidth and availheigth omit the toolbar.
Document
Each window object has a document object to be rendered. These objects get confused in part because HTML elements are added
to the global object when assigned a unique id.
