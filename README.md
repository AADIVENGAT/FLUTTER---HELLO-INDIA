# FLUTTER---HELLO-INDIA
This code has been eecuted in Visual Studio Code

#code:

import 'package:flutter/material.dart';

void main() {
  runApp(GeeksForGeeks());
}

class GeeksForGeeks extends StatelessWidget {
  Widget build(BuildContext context) {
    // Material App
    return MaterialApp(

        // Scaffold Widget
        home: Scaffold(
      appBar: AppBar(
        // AppBar takes a Text Widget
        // in it's title parameter
        title: Text('AADITYA'),
      ),
      body: Center(child: Text('HELLO INDIA')),
    ));
  }
}

#end of code:
