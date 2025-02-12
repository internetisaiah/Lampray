# Customizing Lampray

> Learn how to customize Lampray's fonts, transparency, color theme, and more.

## Prerequisites

Before you can customize Lampray, you'll need to complete one of the following:

- [Download the latest release](../README.md#quick-start)
- [Build from source](./building-from-source.md).

## Setting the path to 7-Zip

In most cases, Lampray can find your 7-Zip installation automatically. However, if it's located in a non-standard location, you'll need to manually set the path to `7z.so` in Lampray.

First open `~/Lampray/Config/config.mdf` in your text editor, then find and replace the following line with the path to your `7z.so` utility.

```sql
<bit7zLibaryLocation>/usr/lib/p7zip/7z.so</bit7zLibaryLocation>
```

## Customizing your font

You can customize your font by creating a `Lamp_Font` directory within `Lamp_Data` and adding a `.ttf` file. Your file tree should be similar to the following:

```bash
Lamp_Data
├── Archives
├── Config
├── Deployment
├── Lamp_Font 
│   └── terminus.ttf
└── Mod_Lists
```

## Customizing your color theme

You can customize your color theme by editing `Lamp_Data/Config/Conf.mdf`.

### Pre-made Colour Schemes

#### Default

```sql
<Colour_WindowBackground>0f0f0f-ef</Colour_WindowBackground>
<Colour_MenuBar>232323-ff</Colour_MenuBar>
<Colour_Text>ffffff-ff</Colour_Text>
<Colour_Button>4296f9-66</Colour_Button>
<Colour_Hover>4296f9-ff</Colour_Hover>
<Colour_Pressed>0f87f9-ff</Colour_Pressed>
<Colour_InputBG>28497a-89</Colour_InputBG>
<Colour_Separator>6d6d7f-7f</Colour_Separator>
<Colour_SearchHighlight>4c004c-ff</Colour_SearchHighlight>
```

#### Light Mode

```sql
<Colour_WindowBackground>efefef-ff</Colour_WindowBackground>
<Colour_MenuBar>dbdbdb-ff</Colour_MenuBar>
<Colour_Text>000000-ff</Colour_Text>
<Colour_Button>4296f9-66</Colour_Button>
<Colour_Hover>4296f9-ff</Colour_Hover>
<Colour_Pressed>0f87f9-ff</Colour_Pressed>
<Colour_InputBG>ffffff-ff</Colour_InputBG>
<Colour_Separator>636363-9e</Colour_Separator>
<Colour_SearchHighlight>4c004c-ff</Colour_SearchHighlight>
<Colour_ToolTipAndTypes>ffffff-f9</Colour_ToolTipAndTypes>
```

#### ImGui 

```sql
<Colour_WindowBackground>0f0f0f-ef</Colour_WindowBackground>
<Colour_MenuBar>232323-ff</Colour_MenuBar>
<Colour_Text>ffffff-ff</Colour_Text>
<Colour_Button>4296f9-66</Colour_Button>
<Colour_Hover>4296f9-ff</Colour_Hover>
<Colour_Pressed>0f87f9-ff</Colour_Pressed>
<Colour_InputBG>28497a-89</Colour_InputBG>
<Colour_Separator>6d6d7f-7f</Colour_Separator>
<Colour_SearchHighlight>4c004c-ff</Colour_SearchHighlight>
<Colour_ToolTipAndTypes>141414-ef</Colour_ToolTipAndTypes>
```

#### ImGui Classic

```sql
<Colour_WindowBackground>000000-d8</Colour_WindowBackground>
<Colour_MenuBar>66668c-cc</Colour_MenuBar>
<Colour_Text>e5e5e5-ff</Colour_Text>
<Colour_Button>59669b-9e</Colour_Button>
<Colour_Hover>667ab5-c9</Colour_Hover>
<Colour_Pressed>7589cc-ff</Colour_Pressed>
<Colour_InputBG>6d6d6d-63</Colour_InputBG>
<Colour_Separator>7f7f7f-99</Colour_Separator>
<Colour_SearchHighlight>4c004c-ff</Colour_SearchHighlight>
<Colour_ToolTipAndTypes>1c1c23-ea</Colour_ToolTipAndTypes>
```

#### Warlock Purple

```sql
<Colour_SearchHighlight>a61103-ff</Colour_SearchHighlight>
<Colour_Text>ffffff-ff</Colour_Text>
<Colour_WindowBackground>0d0f12-ff</Colour_WindowBackground>
<Colour_ToolTipAndTypes>141414-ff</Colour_ToolTipAndTypes>
<Colour_InputBG>2a0033-ff</Colour_InputBG>
<Colour_MenuBar>3a196d-ff</Colour_MenuBar>
<Colour_Button>300159-ff</Colour_Button>
<Colour_Hover>6703a6-ff</Colour_Hover>
<Colour_Pressed>260101-ff</Colour_Pressed>
<Colour_MenuItems>5f80a7-4f</Colour_MenuItems>
<Colour_HeadHover>4296f9-cc</Colour_HeadHover>
<Colour_HeadPressed>4296f9-ff</Colour_HeadPressed>
<Colour_Separator>2a0133-ff</Colour_Separator>
<Colour_SeparatorHover>1966bf-c6</Colour_SeparatorHover>
```

#### Discord's Clyde's Ai Generated Scheme

```sql
<Colour_WindowBackground>51216B-ef</Colour_WindowBackground>
<Colour_MenuBar>EFD951-ff</Colour_MenuBar>
<Colour_Text>ffffff-ff</Colour_Text>
<Colour_Button>75EF51-66</Colour_Button>
<Colour_Hover>75EF51-ff</Colour_Hover>
<Colour_Pressed>EF7551-ff</Colour_Pressed>
<Colour_InputBG>5151EF-89</Colour_InputBG>
<Colour_Separator>EF5151-7f</Colour_Separator>
<Colour_SearchHighlight>4c004c-ff</Colour_SearchHighlight>
<Colour_ToolTipAndTypes>000CF2-ef</Colour_ToolTipAndTypes>
```
