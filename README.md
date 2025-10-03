# Getting started with Syncfusion .NET MAUI Rich Text Editor control

## Overview
The .NET MAUI Rich Text Editor provides a simple yet powerful editor interface to compose richly formatted text with all the common formatting options like bold and italics. The Rich Text Editor is used to create messaging applications, email composers, blog editors, forum post text boxes, feedback and review sections, notes sections, and more. It has a variety of tools to edit and format rich content and returns valid HTML markup content.

## Creating an application with Rich Text Editor
1. Create a new .NET MAUI application in Visual Studio.
2. Syncfusion .NET MAUI components are available in [nuget.org.](https://www.nuget.org/)
3. To add SfRichTextEditor to your project, open the NuGet package manager in Visual Studio, search for `Syncfusion.Maui.RichTextEditor` and then install it.
4. Initialize the `SfRichTextEditor`.

#### XAML

```xml
<ContentPage . . .
             xmlns:rte="clr-namespace:Syncfusion.Maui.RichTextEditor;assembly=Syncfusion.Maui.RichTextEditor">

    <Grid>
        <rte:SfRichTextEditor/>
    </Grid>

</ContentPage>
```

#### C#

```C#
using Syncfusion.Maui.RichTextEditor;

public partial class MainPage : ContentPage
{
    public MainPage()
    {
        InitializeComponent();
        SfRichTextEditor richTextEditor = new SfRichTextEditor();
        this.Content = richTextEditor;
    }
}
```

### Output
[Add the image]

## Troubleshooting

### Path Too Long Exception

If you are facing a "Path too long" exception when building this example project, close Visual Studio and rename the repository to a shorter name before building the project.


