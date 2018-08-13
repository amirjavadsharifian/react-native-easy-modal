# react-native-easy-modal
A simple <Modal/> component for React-native, support Android and IOS

## Install
```
npm install react-native-easy-modal@latest --save
```

## Usage example
```jsx
<Button onPress={() => this.refs.modal1.toggleVisible()}>Basic modal</Button>

<Modalbox ref="modal1">
    <Text>test</Text>
</Modalbox>
```

## Properties

| Prop  | Default  | Type | Allowed values | Description | Required
| :------------ |:---------------:| :---------------:| :-----| :-----| :-----|
| animation | fade | `string` | none, slide, fade | This prop controls how the modal animates. | NO
