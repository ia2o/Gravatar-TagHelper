# Gravatar-TagHelper

Inspired and helped massive along by Andrew Freemantles excellent Gravatar Html Helper here: https://github.com/AndrewFreemantle/Gravatar-HtmlHelper

# A .NET Core 1.0 TagHelper extension for Gravatar

What's Gravatar? https://en.gravatar.com/

1. Drop the .cs file into your project.
2. Add the `@addTagHelper *, [ProjectName]` to your _ViewImport.cshtml file, then use the <gravatar /> tag:


<gravatar email-address="bobisawesome@awesome.net"></gravatar>
