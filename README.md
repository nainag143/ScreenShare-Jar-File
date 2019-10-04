# ScreenShare-Jar-File
Remote Desktop Access Using Java


***Steps To Install**

Download tyhe Client.jar file
Add to your Program


Sample Codee for Server

<pre>

import java.io.IOException;
import java.net.Socket;
import java.net.UnknownHostException;

import javax.xml.stream.events.StartDocument;

import client.*;
import server.InitConnection;

 

public class demo {

	public static void main(String[] args) throws UnknownHostException, IOException {
		// TODO Auto-generated method stub

	 
		
		//To Create Server Use below Function
		new InitConnection(Integer.parseInt("4907"),"123");
		
		 
			
	   
	}

	
	
	
	
</pre>




****Sample Code for Client
****

<pre>  

import java.io.IOException;
import java.net.Socket;
import java.net.UnknownHostException;

import javax.xml.stream.events.StartDocument;

import client.*;
import server.InitConnection;

 

public class demo {

	public static void main(String[] args) throws UnknownHostException, IOException {
		// TODO Auto-generated method stub

	 
		
		//To Create Server Use below Function
		new InitConnection(Integer.parseInt("4907"),"123");
		
		
		//To Create Client
		
		 Start.initialize("172.18.16.81",4907);
		   
			
	   
	}

	
	
	
	
</pre>

