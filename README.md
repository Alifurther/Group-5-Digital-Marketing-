import 'package:flutter/material.dart';
void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          centerTitle: true, 
          backgroundColor: const Color.fromARGB(220, 14, 175, 114),
          title: Text("DIGITAL MARKETING")),
        body: ListView(
          padding: EdgeInsets.only(left: 50, right: 50),
          children: [
            Card(
               color: Colors.blueAccent,
              child: ListTile(
                leading: Text('1'),
                trailing: Icon(Icons.ads_click),
                title: Text("INTRODUCTION TO DIGITAL MARKETING"),
                subtitle: Text("Basic Of Digital Marketing") ,)),
             
               Card(
                 color: const Color.fromARGB(255, 2, 202, 252),
              child: ListTile(
                leading: Text('2'),
                trailing: Icon(Icons.ads_click),
                title: Text("SOCIAL MEDIA MARKETING"),
                subtitle: Text("Channels Of Social Media Marketing"),
                )),

                  Card(
                     color: Colors.blueAccent,
              child: ListTile(
                leading: Text('3'),
                trailing: Icon(Icons.ads_click),
                title: Text("SEO"),
                subtitle: Text("Metrics Of Search Engine Optimization"))),

                  Card(
                     color: const Color.fromARGB(255, 2, 202, 252),
              child: ListTile(
                leading: Text('4'),
                trailing: Icon(Icons.ads_click),
                title: Text("FREELANCING"),
                subtitle: Text("Freelancing platforms"))),

                  Card(
                    color: Colors.blueAccent,
              child: ListTile(
                leading: Text('5'),
                trailing: Icon(Icons.ads_click),
                title: Text("CONTENT MARKETING"),
                subtitle: Text("Social Media Brand"))),
             
             
             
             
    

          ],
        ),
      ),
    )
  );
}
