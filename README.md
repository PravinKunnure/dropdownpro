# dropdownpro
A customisable dropdown overlay package for Flutter.
=======
# DropdownPro

A **customizable dropdown overlay package for Flutter**.  

## Features

- Customizable dropdown overlay
- Easy to integrate in any Flutter app

## Installation

Add this in your `pubspec.yaml`:

```yaml
dependencies:
  dropdownpro:
    git:
      url: https://github.com/yourusername/dropdownpro.git
      ref: main


##Usage

import 'package:flutter/material.dart';
import 'package:dropdownpro/dropdownpro.dart';

HSFlowDropdownBasic(
  label: "Select Fruit",
  items: ["Apple", "Banana", "Orange", "Mango"],
  onItemSelected: (value) {
    print("Selected: $value");
  },
);
