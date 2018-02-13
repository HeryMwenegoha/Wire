Follows the implementaion of the TWI library by Nicholas Zambetti
  
  By : Hery A Mwenegoha
  I have modified the library to include functions that were useful to me:-
  The functions should be self explanatory.
  uint8_t* readReg(const uint8_t addr, const uint8_t reg, uint8_t len);
	uint8_t	 read8(const uint8_t addr, const uint8_t reg);
	bool 	 write8(const uint8_t addr, const uint8_t reg, uint8_t data);
	bool 	 readBytes(uint8_t addr, uint8_t reg, uint8_t len, uint8_t *des);
