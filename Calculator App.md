# Calculator-App

*Calculator App*



This is a basic calculator App that i built using core Java and the Swing framework. 
Some of the functions included in the calculator include 

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
