# HomeWork4
import 'dart:io';
import 'package:dart_application_2/dart_application_2.dart' as dart_application_2;
String answer = (stdin.readLineSync().toString()!);
void main(List<String> arguments) {

print("Please Enter the first student grade:");
int student1 = int.parse(stdin.readLineSync()!);
print("Please Enter the Secound student grade:");
int student2 = int.parse(stdin.readLineSync()!);
print("Please Enter the Thired student grade:");
int student3 = int.parse(stdin.readLineSync()!);

print("The Student grades are");
print("First Stduent : $student1");
print("Secound Stduent : $student2");
print("Thired Stduent : $student3");
print("is that correct ?" );
if(answer == "yes"){
if(student1==student2 && student2==student3 ){
print("The All Student Grades are equal");
}else if(student1 > student2 && student1>student3 ){
print("The First Student got higher Mark");
}else if(student2 > student1 && student2>student3 ){
print("The Secound Student got higher Mark");
}else if(student3 > student1 && student3>student2 ){
print("The Thired Student got higher Mark");
}
}else{
  print("Please Try Again");
}
  }
