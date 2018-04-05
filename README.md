# This tutorial is to understand states and props in the React JS Component


## What are the different `props types`

```
App.propTypes = {
  propObject: React.PropTypes.object,
  propString: React.PropTypes.string,
  propNumber: React.PropTypes.number
}
```


## How to create `pros` and use them in the component

Creating Default Props

```
App.defaultProps = {
  propNumber: 3,
  propString: "THis is prop string",
  propObject: {
    obj1: "I am obj 1",
    obj2: "I am obj 2",
    obj3: "I am obj 3"
  }
}
```

Using `props` in the component

```
 <h3>prop number is : {this.props.propNumber}</h3>
 <h3>prop number is : {this.props.propString}</h3>
 <h3>prop number is : {this.props.propObject.obj1}</h3>
```


## How to create and use `state` object


## How to create an `onClick` event on the Element
