# React

## Basic

### Lifecycle Hooks

>order

 - Mounting Phase
constructor()->render()->componentDidMount()

 - Updating Phase
render()->componentDidUpdate()

 - Unmounting Phase
componentWillUnmount()

 - constructor

```
    constructor(props) {
        super(props)
        this.state = this.props.something //✅
        this.setState({this.props.something})  //❌
        // setState can only be called component mounted
    }
-
```
```
// a place to decide wheather ajax call to update component
componentDidUpdate(prevProps, prevState) {
    console.log("preProps", preProps)
    console.log("preState", preState)

    if (prevProps.counter.value !== this.props.counter.value) {
    // ajax call axios.get(url)
    }
    }
