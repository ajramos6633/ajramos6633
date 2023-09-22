- 👋 Hi, I’m @ajramos6633
- 👀 I’m interested in ...wrestling 
- 🌱 I’m currently learning ...Java 
- 💞️ I’m looking to collaborate on ...I do nor know 
- 📫 How to reach me ...100144843@lubbockisd.net
  

<!---
ajramos6633/ajramos6633 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->import static java.lang.System.*;

public class Main {
    public static void main(String[] args) {

        Bug dude = new Bug(35,false);  //instantiation
        Bug dudette = new Bug(25,true);
        Bug dudekid = new Bug();

        dudette.speak();
        dudekid.speak();
        dudekid.speak();
        dudette.sayName();
        dude.sayName();

        dude.setFly(true);
        dudette.setSize(43);


        int ans = dudette.multiplicator(7,9);
        out.println("the answer is " + ans);

        //static methods
        //mostly in library/helper classes

        //The Math class

        out.println(Math.pow(3,7));


        // Random Numbers (RNG)  (PNG)
        //  Math.random() ==>  [0.0, 1.0)

        // range = upper - lower + 1
        // (int)(Math.random() * range + lower)

        int d6 = (int)(Math.random()*6 + 1);
        out.println("you rolled: " + d6);


        //Strings
        //          0123456789
        String s = "howdy yall";
        //strings are immutable

        out.println(s.charAt(4));
        out.println(s.length());
        out.println(s.substring(3));    // from spot to the end
        out.println(s.substring(3,7));          // from first up to but not including second
        out.println(s.indexOf("owd"));
        out.println(s.indexOf("dog"));
        out.println(s.lastIndexOf("all"));
        out.println(s.indexOf("y"));
        out.println(s.lastIndexOf("y"));

        s.toUpperCase();
        out.println(s);
        s = s.toUpperCase();
        out.println(s);

        String s1 = "one";
        String s2 = "two";
        // equals     and      compareTo
        out.println(s1.equals(s2));
        out.println(s1.compareTo(s2));
        out.println(s2.compareTo(s1));


    }
