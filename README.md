class Jala {
	public static void main(String[] args) {
		int a[] = { 3, 5, 6, 7 };
		try {
			Class.forName("Yeshwanth");
		} catch (ClassNotFoundException ae) {
			System.out.println("The class is not found : " + ae);
		} finally {
			System.out.println("Byeee!!!!");
		}
	}
}
