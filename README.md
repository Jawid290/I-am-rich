# I-am-rich



import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
        home: Scaffold(
          backgroundColor: Colors.blueGrey,
      appBar: AppBar(
          backgroundColor: Colors.blueGrey[900],
          title: Center(child: Text('I am rich'))),
          body: Center(
            child: Image(
              image: NetworkImage('https://th.bing.com/th/id/OIP.9cNXe-HD7iGqBfafnWLUbAHaFU?pid=ImgDet&w=500&h=359&rs=1'),
            ),
          ),
    )),
  );
}
