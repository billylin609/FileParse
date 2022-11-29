#ifndef DataPattern_H
#define DataPattern_H

/*
 * The data format we will be recieveing on Sunday is
 * data[1] = ((uint8_t) << 8) | (uint8_t)) & 0XFF
 * [0]
 * data[1] = ((uint8_t) << 8) | (uint8_t)) & 0XFF
 * [0]
 * data[1] = ((uint8_t) << 8) | (uint8_t)) & 0XFF
 * [0]
 * data[1] = ((uint8_t) << 8) | (uint8_t)) & 0XFF
 * [0]
 * data[1] = ((uint8_t) << 8) | (uint8_t)) & 0XFF
 * [0]
 * data[1] = ((uint8_t) << 8) | (uint8_t)) & 0XFF
 * [0]
 * [0]
 */

/*But in the file each single line is defined as
 * Time stamp: b'decimal value' //at max three lien for a three digits decimal value
 * Time Stamp: b'\r'
 * Time Stamp: b'\n'
 */

const std::string OF_Header = "Result/";
const std::string IF_Header = "Drop_Here/";

class DataPattern {
	private:
		std::ifstream input_file;
		std::ofstream output_file;

		char end_time_stamp = ':';
		char start_num  = '\'';
	
	public:
	       DataPattern();

	       void read_line();
};

#endif
