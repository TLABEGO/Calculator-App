# Calculator-App

*Calculator App*



This is a basic calculator App that i built using core Java and the Swing framework. 
I listed some of the functions that the calculator posssess below: 
* Computing addition calculations
* Computing subtraction calculations
* Computing multiplicatin calculations
* Computing devision calculations

*The picture below shows how the calculator looks like in action.*

![](https://github.com/TLABEGO/Calculator-App/blob/master/sample.png)

*Check out some of the code snippets that i used to launch the application, create the application and initialize the contents of the frame below*


*Launching the application*

```java
/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Calculator window = new Calculator();
					window.frame.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}
  ```
  
  
  
  
  *Creating the application*
 ```java
 /**
	 * Create the application.
	 */
	public Calculator() {
		initialize();
	}

 ```





*Initializing the contents of the frame*
```java
	/**
	 * Initialize the contents of the frame.
	 */
	private void initialize() {
		frame = new JFrame();
		frame.setBounds(100, 100, 307, 424);
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame.getContentPane().setLayout(null);

		textField = new JTextField();
		textField.setHorizontalAlignment(SwingConstants.RIGHT);
		textField.setFont(new Font("Tahoma", Font.BOLD, 20));
		textField.setBounds(10, 11, 274, 53);
		frame.getContentPane().add(textField);
		textField.setColumns(10);
```

***

### Copyright
*MIT

Copyright (c) <2020> <MIT>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

