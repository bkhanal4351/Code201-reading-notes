**Ch.4 “Links”**

a LInk or Hyperlink is used to create a source to jump from one page to another. Links in HTML are crated using <a> tag. An example is : 
<a href="https://github.com/bkhanal4351/Code201-reading-notes/blob/main/class03.md"</a>

**Chapter 15: “Layout”**

Layouts are used to make the look of a webpage better. There are a few elements used that are considered layouts such as:

1. Header
2. Navigation
3. Content
4. Footer
5. Navigation bar

**“Functions, Methods, and Objects”**

Functions are group of reusable codes which can be called anywhere. This eliminates the need to writing the same set of codes time and again. A function only executes when called. An example of function would be:

function propmtUserForInput(whichPrompt) {
    if (!whichPrompt) {
        whichPrompt = 'How many pictures of Nepal would you like to see?';
    }
    let picCount = prompt (whichPrompt);
    if (picCount >2 ){
        let message = 'How many pictures of Nepal would you like to see?';
        let error = 'Please enter either 1 or 2';
        propmtUserForInput(message + error);
    }

    if (picCount == '' ){
        let message = 'How many pictures of Nepal would you like to see?';
        let error = 'Please enter either 1 or 2';
        propmtUserForInput(message + error);
    }

    if (picCount == 1) {
        let counter = 0;
        while (counter < 1){
            document.write ('<img src= "images/Nepal.jpg ">');
            counter++;
        }
    }

        if (picCount == 2) {
            let counter = 0;
            while (counter < 2){
                document.write ('<img src= "images/Nepal.jpg ">');
                counter++;
            }
        }
    
    
}

 propmtUserForInput();


