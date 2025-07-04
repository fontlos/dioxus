# Examples

These examples are fully-fledged mini Dioxus apps.

You can run them with `cargo run --example EXAMPLE_NAME`. Example:

```shell
cargo run --example hello_world
```

(Most of these examples are run through webview, so you don't need the Dioxus CLI installed)

## Basic Features

[hello_world](./hello_world.rs) - Most basic example

[readme](./readme.rs) - Counter example from the Readme

[custom_assets](./custom_assets.rs) - Include images

[custom_html](./custom_html.rs) - Customize wrapper HTML

[eval](./eval.rs) - Evaluate JS expressions

### RSX

[rsx_usage](./rsx_usage.rs) - Demo of all RSX features

[xss_safety](./xss_safety.rs) - You can include text without worrying about injections by default

### Props

[optional_props](./optional_props.rs) - Optional props

### CSS

[tailwind](./tailwind/) - You can use a library for styling

## Input Handling

[all_events](./all_events.rs) - Basic event handling demo

[file upload](./file_upload.rs) - Handle uploading files

[form](./form.rs) - Handle form submission

[nested_listeners](./nested_listeners.rs) - Nested handlers and bubbling

### State Management

[context_api](./context_api.rs) - Cross-component state sharing via Context API

[counters](./counters.rs) - Mapping a `Signal<Vec<T>>` into UI elements

[futures](./future.rs) - Handle async Rust with use_future, use_effect, and async event handlers

### Async

[login_form](./login_form.rs) - Login endpoint example

[suspense](./suspense.rs) - Render placeholders while data is loading

### SVG

[svg](./svg.rs)

## Server-side rendering

[ssr](./ssr.rs) - Rendering RSX server-side

[hydration](./hydration.rs) - Pre-rendering with hydration

## Common Patterns

[disabled](./disabled.rs) - Disable buttons conditionally

[errors](./errors.rs) - Handle errors with early return

## Routing

[flat_router](./flat_router.rs) - Basic, flat route example

[router](./router.rs) - Router example

[link](./link.rs) - Internal, external and custom links

## Platform Features

[window_event](./window_event.rs) - Window decorations, fullscreen, minimization, etc.

[window_zoom](./window_zoom.rs) – Zoom in or out

[popup](./popup.rs) - Create a popup window and send data back to the main window

## Example Apps

[calculator](./calculator.rs) - Simple calculator

[crm](./crm.rs) - Toy multi-page customer management app

[dog_app](./dog_app.rs) - Accesses dog API

[todomvc](./todomvc.rs) - Todo task list example
