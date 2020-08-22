This is just a RAM saving version of original webconfig.
Small changes like controls alignment and utf-8 in header.
Just maybe someone find it useful.

Usage:

void readConf()
{
	String params = F("["
	                  "{"
	                  "'name':'dev_pwd',"
	                  "'label':'Device pass',"
	                  "'type':");
	params += String(INPUTPASSWORD);
	params += F(","
	            "'default':'XXXXXX'"
	            "},"
	            "{"
	            "'name':'ssid1',"
	            "'label':'WiFi name',"
	            "'type':");
	params += String(INPUTTEXT);
	params += F(","
	            "'default':'SSID1'"
	            "},"
	            "{"
	            "'name':'pwd1',"
	            "'label':'WiFi pass',"
	            "'type':");
	params += String(INPUTPASSWORD);
	params += F(","
	            "'default':'my_pass_1'"
	            "},"
	            "{"
	            "'name':'ssid2',"
	            "'label':'WiFi name',"
	            "'type':");
	params += String(INPUTTEXT);
	params += F(","
	            "'default':'SSID2'"
	            "},"
	            "{"
	            "'name':'pwd2',"
...
