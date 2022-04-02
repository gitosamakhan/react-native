<h1 align="center">React Native</h1>

<details>
<summary>Fundamental Concepts </summary>

## Core Components & API's

- View
- Text
- Image
- Button
- Touchables
- Alert

## Views

In react native, we dont have `<div></div>`. instead of a `div`, we can use a `View`. Make sure to keep it CamelCase, unlike in react. Best to apply styles on these Views.

## Text

We cannot use text anywhere, just like in Web, always use `<Text></Text>`. Some props that we can use with `Text` are:

    <Text numberOfLines={1} onPress={() => console.log("Pressed")}>
        Hello World
    </Text>

</details>
