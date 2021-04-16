# Gravatar-TagHelper

Inspired and helped massive along by Andrew Freemantles excellent Gravatar Html Helper here: https://github.com/AndrewFreemantle/Gravatar-HtmlHelper

# An ASP.NET Core TagHelper extension for Gravatar - tested with Core 1, 1.1, 2.1 and 3.1

What's Gravatar? https://en.gravatar.com/

1. Drop the .cs file into your project.
2. Add `@addTagHelper *, [ProjectName]` to your `_ViewImport.cshtml` file in the `Views` folder, then use the `<gravatar />` tag freely.

For example: `<gravatar email-address="awesomeness@awesome.net"></gravatar>`

The tag attributes are:

* EmailAddress: The email of the Gravatar user - use this from a logged in user
* ImageSize: the size of the image returned, default 80px
* DefaultImage: the default image returned. An enum will allow you to select from the Gravatar defaults
* DefaultImageUrl: If you wish to use a different image as the default, supply the URL here (relative or absolute)
* ForceDefaultImage: Forces the default image over the Gravatar image
* Rating: the allowed maturity rating for the image returned - Defaults to "G" for generally acceptable and will block anything rated PG, R, or X
* AdditionalCssClasses: specifcy the additional CSS classes you would like applied to the returned image
* ForceSecureRequest [Obsolete]
