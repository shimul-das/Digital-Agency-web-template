#HTML New Tag
- proress 
- meter 
- Details ===tag( summary + p )

# code
    <progress id="one">32%</progress>
    <meter value="0.5"></meter>
    <details>
        <summary>wow</summary>
        <p>hero</p>
        <p>heo</p>
    </details>

# Attribude
    image=Loading="lazy". that time we use it only load scrollable img
    <h1><bdo dir="rtl">Hellow word</bdo></h1> == opposite direction
# imoji set in cursor
.test{
    background-color: aquamarine;
    cursor:url("asset/So\ so\ happy\ emoji!.cur"),auto;
}

# Flex Concept
=> Grid 2 dimentional.
=> Flex Single dimention.

<div class="parent">
    <div class="child">1</div>
    <div class="child">2</div>
    <div class="child">3</div>
</div>

.parent{
    display: flex;
    flex-direction:row;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}
.child{
    order:3;
    flex-grow: 2;
    background-color: bisque;
    width: 200px;
    height: 200px;
    padding: 20px;
    margin: 10px;
}

