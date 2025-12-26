# Remove Controls

<Badge type="tip" vertical="top" text="Elementor Core" /> <Badge type="warning" vertical="top" text="Intermediate" />

To remove existing control developers can simply unregister existing control by passing the control name.

## Hooks

To do that we need to hook to the `elementor/controls/register` action which 
	$controls_manager->unregister( 'control-2' );

}
add_action( 'elementor/controls/register', 'unregister_controls' );
```
