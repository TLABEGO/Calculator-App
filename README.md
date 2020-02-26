# Calculator-App

## Calculator

This is a basic calculator App that was build using core Java and the Swing framework. The above picture shows exactly how the  calculator looks like in action.

copyright;  MIT

Check out the some of the code snippeds below 


```java
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
