### Code:

``` 
  if (hungry) {
    switch (true) {
    case availableTime <= 30 && availableTime >= 20:
      console.log(`Need to put the lunch in a place nearby.`);
      break;
    case availableTime < 20:
      console.log(`Should get something to eat and eat it in the lab.`);
      break;
    default:
      console.log(`We shouldnt spend too much time eating cause we in bootcamp.`);
      break;
    }
  } else {
    console.log(`Should get back to work.`);
  }
  
};

```