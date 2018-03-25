# js-search
**A search algorithm written in javascript under 1 kilobyte!**
# How to use  
`searchg(term, data)`  
**ex:**  
*Input*  
`searchg("bob",["bob","cool","bob"]) `  
*Output*  
 `
{text: "I like bob.", index: 0, score: 1}  
{text: "Bob isn't cool...", index: 1, score: 0.998}  
{text: "Bob has a lot of friends", index: 2, score: 0.995}  
 `
