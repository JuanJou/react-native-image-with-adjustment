# Still in development

## React Native Image with Adjustment

This is a component for react native to display images. It inherits all funcionality of the base react native image components, and adds three more props to change image's saturation, brightness and contrast. It also accepts a prop called `code`save`code`

`code`
<ImageWithAdjustment
    brightness={this.state.brightness}
    saturation={this.state.saturation}
    contrast={this.state.contrast}
    src={{
	source: [
	    uri: uri
	],
	width: 1920,
	height: 1080,
    }}
    reizeMode='contain'
    onSave={this.onSave}
    save={this.triggerSave}
/>
`code`

