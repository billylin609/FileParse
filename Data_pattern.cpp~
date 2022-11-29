#include <iostream>
#include <fstream>
#include <string>
#include "Data_pattern.h"


DataPattern::DataPattern() {
	static const std::string target_file = "testCopy.txt";
	input_file.open(IF_Header + target_file);
	if (!input_file.is_open()) {
		std::cout << "file_not_open" << std::endl;
	}
	for(std::string current_line; std::getline(input_file, current_line);) {
		std::cout << current_line << std::endl;
	}
}

int main () {
	DataPattern test;

	return 0;
}
