# Android-ListView-or-GridView-inside-ScrollView

This project will help you to how to use Android ListView and Android GridView inside ScrollView.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

```
Android Studio
Knowlege of Android ListView, GridView and ScrollView
```

## How to use

```
//ListView
CustomListView  listView = new CustomListView(this);
 
listView.setAdapter(adapter);
listView.setExpanded(true);
```

```
//GridView
CustomGridView  gridView = new CustomGridView (this);
 
gridView.setNumColumns(5);
gridView.setAdapter(adapter);
gridView.setExpanded(true);
```

## Built With
* [Android Studio](https://developer.android.com/studio/index.html)

## Authors

* **Harsh Shah** - *Initial work* - [Tweezer](https://github.com/harsh1711/Tweezer)
