## Assignment-8 Answer

```
let parent = document.getElementById("SIvCob");

let i = 0;
while(i < parent.children.length){
    if(i % 2 == 0){
        let elm = parent.children[i];
        parent.removeChild(elm);
    }
    i++;
}

```

![Code](./ss1.jpg)

![Output](./ss2.jpg)


---

## 8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](../Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed

### Output

![Output](../Pic15.png)