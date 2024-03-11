class Shapes {
    public double perimeter() {
        return 0.0;
    }
}

class Circle extends Shapes {
    private double radius;

    public Circle(double radius) {
        this.radius = radius;
    }

    @Override
    public double perimeter() {
        return 2 * Math.PI * radius;
    }
}

class Square extends Shapes {
    private double side;

    public Square(double side) {
        this.side = side;
    }

    @Override
    public double perimeter() {
        return 4 * side;
    }
}

class Rectangle extends Shapes {
    private double length;
    private double width;

    public Rectangle(double length, double width) {
        this.length = length;
        this.width = width;
    }

    @Override
    public double perimeter() {
        return 2 * (length + width);
    }
}

class Triangle extends Shapes {
    private double side1;
    private double side2;
    private double side3;

    public Triangle(double side1, double side2, double side3) {
        this.side1 = side1;
        this.side2 = side2;
        this.side3 = side3;
    }

    @Override
    public double perimeter() {
        return side1 + side2 + side3;
    }
}

public class Main {
    public static void main(String[] args) {
       
        Circle circle = new Circle(5.0);
        Square square = new Square(4.0);
        Rectangle rectangle = new Rectangle(3.0, 5.0);
        Triangle triangle = new Triangle(3.0, 4.0, 5.0);

        System.out.println("Perimeter of circle: " + circle.perimeter());
        System.out.println("Perimeter of square: " + square.perimeter());
        System.out.println("Perimeter of rectangle: " + rectangle.perimeter());
        System.out.println("Perimeter of triangle: " + triangle.perimeter());
    }
}
