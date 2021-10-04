# this is the project for learning Dear ImGui and immediate mode GUI concept.

Dear ImGui is an immediate mode GUI library which makes making GUI for all kinds of tools very easy.

Immediate mode GUI is a bit different to what people think when they hear “GUI” (“retained mode” is a classic way of doing GUI). Immediate mode GUI is a way of doing GUI which involves creating and drawing widgets in each frame. Instead of creating some Button object and adding a callback to it, you write something like

```cpp
if (ImGui::Button("Some Button")) {
    ... // code which will be called on button pressed
}
```

Simple as that!

For a great in-depth talk on this concept, I recommend to check out [Casey Muratori’s talk on IMGUI](https://caseymuratori.com/blog_0001).
