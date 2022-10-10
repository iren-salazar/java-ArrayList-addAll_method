# java-ArrayList-addAll_method

package personal;

import java.util.ArrayList;

public class MoreArrayList {
	public static void main(String[] args) {

		ArrayList <Double> numbers = new ArrayList <> ();
		numbers.add(4.0);
		numbers.add(5.0);
		System.out.println("\rfirst numbers: " + numbers);
		
		ArrayList <Double> secNums = new ArrayList <> ();
		secNums.add(1.0);
		secNums.add(2.0);
		secNums.add(3.0);
		System.out.println("\rSecond numbers: " + secNums);
		
		ArrayList <Double> upNums = new ArrayList <>();
		upNums.add(6.0);
		upNums.add(7.0);
		upNums.add(8.0);
		upNums.add(9.0);
		upNums.add(10.0);
		numbers.addAll(upNums);
		
		System.out.println("\rUpdated numbers: " + secNums + numbers );
	}
}
