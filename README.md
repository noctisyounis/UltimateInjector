# Ultimate Injector

**Package version : 1.0.0**   
**Unity version : 2020.3+**

## Description

This tool helps you link a *[ScriptableObject](https://docs.unity3d.com/ScriptReference/ScriptableObject.html)*'s property value to another *[Component](https://docs.unity3d.com/ScriptReference/Component.html)*'s property value.

### How to use
Add the *DataInjector* to a *[GameObject](https://docs.unity3d.com/ScriptReference/GameObject.html)* on the scene.

Link the Source *[ScriptableObject](https://docs.unity3d.com/ScriptReference/ScriptableObject.html)* and choose the property you want to bind with the target property.

Link the Target *[Component](https://docs.unity3d.com/ScriptReference/Component.html)* and choose the property which will receive the source property value.

If the types match, the "*Inject*" button will be available. Otherwise a warning will be displayed.

During runtime, the value is injected on *[Update](https://docs.unity3d.com/ScriptReference/MonoBehaviour.Update.html)*.

## Features

- DataInjector component.
- Works with any ScriptableObject.
- Custom Inspector for the DataInjector.

## Possible improvements

- Make it works with fields and properties.
- Add parameters to manage when the value is injected.