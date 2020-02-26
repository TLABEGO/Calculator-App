# Calculator-App

*Calculator App*



*This is a basic calculator App that i built using core Java and the Swing framework.
Some of the functions included in the calculator are 
*

*The picture below shows how the calculator looks like in action.*
a) Computing addition calculations
b) Computing subtraction calculations
c) Computing multiplicatin calculations
b) Computing devision calculations

![](https://github.com/TLABEGO/Calculator-App/blob/master/sample.png)

*Check out some of the code snippets below* 


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
  
  
  
  
  
 ```java
 /**
	 * Create the application.
	 */
	public Calculator() {
		initialize();
	}

 ```





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
