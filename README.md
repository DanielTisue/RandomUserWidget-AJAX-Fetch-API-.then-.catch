# Tutorial -RandomUserWidget: AJAX, Fetch(API),.then(),.catch()

* This is a tutorial that utilizes AJAX through the use of fetch(), .then(), and .catch(). Application is done using Html, Css, and Javascript. 

## Summary

Everytime the the 'Next User' button is pressed a New User Profile is generated from the the api. Data is parsed and displayed in a Random User Widget.

* API:   https://randomuser.me/api/

### Additional

This is an alternative method to XHR. It has become a standard for single page apps and currently offers a variety of easily accesible support. 

### Usage: 

    fetch(url)
    .then(function(res){
        console.log(res);
    })
    .catch (function(error) {
        console.log(error);
    });