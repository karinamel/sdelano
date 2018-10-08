# derevo_oop

''C++
#include "stdafx.h"
#include "Tree.h"
#include <iostream>
using namespace std;

Tree::Tree() {
	this->root = nullptr;
}

Tree::Tree(int value) {
	this->root = new Node(value);
}
