# Codemirror Visual Code Material Theme
Codemirror theme that looks close to https://github.com/equinusocio/vsc-material-theme

## About
I could not find any theme to be close to this. The Material theme built into CodeMirror does have the right color codes but looks WAY off. So I create this that looks a lot more close to the final.

It's not impossible but hard and time-consuming to match Visual Code in Codemirror since that would require modification in CodeMirror languages file. We would need to wrap brackets (`{}`) and also fix selectors like `&::-webkit-scrollbar` where the `&` & `::` need to be wrapped in their respective classed element. This is what I came up with basically. If you find an improvement please feel free to create a pull request or send the change to <hi@proux.io>.
