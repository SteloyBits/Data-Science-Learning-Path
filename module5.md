<h2>Module 5: Object-Oriented Programming (OOP) in Python</h2>
    <p><strong>Introduction:</strong> This module introduces Object-Oriented Programming. Learn the fundamentals of classes, objects, inheritance, and more through clear examples.</p>
    
    <h3> 1. Introduction to OOP Concepts</h3>
    <ul>
      <li><strong>What is OOP?</strong>
        <p>Definition and benefits of object-oriented design.</p>
        <pre>
        <code># OOP is a way to structure code using objects.
</code></pre>
      </li>
      <li><strong>Classes and Objects Explained</strong>
        <p>Conceptual explanation with examples.</p>
      </li>
      <li><strong>Real-World Analogies</strong>
        <p>Examples: Cars, Animals, etc.</p>
      </li>
      <li><strong>Comparing Procedural and Object-Oriented Approaches</strong>
        <p>Discussion on different coding paradigms.</p>
      </li>
    </ul>
    
    <h3>2. Defining Classes and Creating Objects</h3>
    <ul>
      <li><strong>Basic Class Definition</strong>
        <pre><code>class Animal:
    pass
</code></pre>
      </li>
      <li><strong>Creating an Instance (Object) of a Class</strong>
        <pre>
        <code>class Animal:
    pass

dog = Animal()
print(dog)
</code></pre>
      </li>
      <li><strong>The <code>__init__</code> Method for Initialization</strong>
        <pre><code>class Animal:
    def __init__(self, name):
        self.name = name

cat = Animal("Whiskers")
print(cat.name)
</code></pre>
      </li>
      <li><strong>Instance Variables vs Class Variables</strong>
        <p>Explanation with code examples.</p>
        <pre><code>class Animal:
    species = "Mammal"  # Class variable
    def __init__(self, name):
        self.name = name  # Instance variable
</code></pre>
      </li>
    </ul>
    
    <h3>3. Methods and Their Uses</h3>
    <ul>
      <li><strong>Defining Instance Methods</strong>
        <pre><code>class Animal:
    def __init__(self, name):
        self.name = name
    def speak(self):
        return f"{self.name} makes a noise."

dog = Animal("Buddy")
print(dog.speak())
</code></pre>
      </li>
      <li><strong>Method Parameters and Self</strong>
        <p>Explanation of the <code>self</code> parameter.</p>
      </li>
      <li><strong>Class Methods vs Static Methods</strong>
        <pre><code>class Animal:
    @classmethod
    def general_info(cls):
        return "Animals are living organisms."
    @staticmethod
    def kingdom():
        return "Animalia"

print(Animal.general_info(), Animal.kingdom())
</code></pre>
      </li>
      <li><strong>Overriding Methods in Child Classes</strong>
        <p>Discussion and examples.</p>
      </li>
    </ul>
    
    <h3>4. Inheritance and Subclasses</h3>
    <ul>
      <li><strong>Concept of Inheritance</strong>
        <p>How subclasses inherit attributes and methods from parent classes.</p>
      </li>
      <li><strong>Creating a Subclass</strong>
        <pre><code>class Dog(Animal):
    def speak(self):
        return f"{self.name} barks."

dog = Dog("Max")
print(dog.speak())
</code></pre>
      </li>
      <li><strong>Using super() to Call Parent Methods</strong>
        <pre><code>class Cat(Animal):
    def __init__(self, name, color):
        super().__init__(name)
        self.color = color
    def speak(self):
        return f"{self.name} meows."

cat = Cat("Luna", "black")
print(cat.speak())
</code></pre>
      </li>
      <li><strong>Multiple Inheritance Overview</strong>
        <p>Simple example and cautionary notes.</p>
      </li>
    </ul>
    
    <h3>5. Encapsulation and Data Hiding</h3>
    <ul>
      <li><strong>Private vs Public Attributes</strong>
        <pre><code>class BankAccount:
    def __init__(self, balance):
        self.__balance = balance  # Private attribute
    def get_balance(self):
        return self.__balance

account = BankAccount(1000)
print(account.get_balance())
</code></pre>
      </li>
      <li><strong>Getter and Setter Methods</strong>
        <pre><code>class BankAccount:
    def __init__(self, balance):
        self.__balance = balance
    def deposit(self, amount):
        self.__balance += amount
    def get_balance(self):
        return self.__balance

account = BankAccount(1000)
account.deposit(500)
print(account.get_balance())
</code></pre>
      </li>
      <li><strong>Benefits of Encapsulation</strong>
        <p>Protection and maintainability of code.</p>
      </li>
      <li><strong>Using Properties for Cleaner Access</strong>
        <pre><code>class BankAccount:
    def __init__(self, balance):
        self.__balance = balance
    @property
    def balance(self):
        return self.__balance

account = BankAccount(1500)
print(account.balance)
</code></pre>
      </li>
    </ul>
    
    <h3>6. Polymorphism and Method Overriding</h3>
    <ul>
      <li><strong>What is Polymorphism?</strong>
        <p>Allowing methods to behave differently on different classes.</p>
      </li>
      <li><strong>Method Overriding in Subclasses</strong>
        <p>Using the same method name in different classes.</p>
      </li>
      <li><strong>Examples of Polymorphism in Python</strong>
        <pre><code>class Bird(Animal):
    def speak(self):
        return f"{self.name} chirps."

animals = [Dog("Rex"), Cat("Mia", "white"), Bird("Tweety")]
for animal in animals:
    print(animal.speak())
</code></pre>
      </li>
      <li><strong>Abstract Classes and Methods (Conceptual Introduction)</strong>
        <p>Using the <code>abc</code> module for abstract classes.</p>
      </li>
    </ul>
    
    <h3>7. Composition: Building Complex Objects</h3>
    <ul>
      <li><strong>Difference Between Inheritance and Composition</strong>
        <p>Explanation with examples.</p>
      </li>
      <li><strong>Using Composition to Build Objects</strong>
        <pre><code>class Engine:
    def start(self):
        return "Engine starting"
class Car:
    def __init__(self, engine):
        self.engine = engine
    def start(self):
        return self.engine.start()

my_car = Car(Engine())
print(my_car.start())
</code></pre>
      </li>
      <li><strong>Benefits of Composition</strong>
        <p>Flexibility and modularity in code design.</p>
      </li>
      <li><strong>Real-World Use Cases</strong>
        <p>Examples in various applications.</p>
      </li>
    </ul>
    
    <h3>8. Special Methods (Magic Methods)</h3>
    <ul>
      <li><strong>The <code>__str__</code> and <code>__repr__</code> Methods</strong>
        <pre><code>class Person:
    def __init__(self, name):
        self.name = name
    def __str__(self):
        return f"Person named {self.name}"
print(Person("Alice"))
</code></pre>
      </li>
      <li><strong>Operator Overloading</strong>
        <pre><code>class Vector:
    def __init__(self, x, y):
        self.x = x
        self.y = y
    def __add__(self, other):
        return Vector(self.x + other.x, self.y + other.y)
    def __str__(self):
        return f"Vector({self.x}, {self.y})"

v1 = Vector(1, 2)
v2 = Vector(3, 4)
print(v1 + v2)
</code></pre>
      </li>
      <li><strong>Implementing Length and Comparison Methods</strong>
        <p>Examples using <code>__len__</code>, <code>__eq__</code>, etc.</p>
      </li>
      <li><strong>Using __init__ for Custom Initialization</strong>
        <p>Advanced initialization techniques.</p>
      </li>
    </ul>
    
    <h3>9. Designing and Organizing Large Programs with OOP</h3>
    <ul>
      <li><strong>Structuring Your Project into Classes and Modules</strong>
        <p>Strategies for maintainable code organization.</p>
      </li>
      <li><strong>Using Packages to Group Related Classes</strong>
        <pre><code><!-- Example Directory Structure:
my_project/
├── animals/
│   ├── __init__.py
│   ├── dog.py
│   └── cat.py
└── main.py -->
</code></pre>
      </li>
      <li><strong>Documenting Your Classes</strong>
        <p>Importance of clear documentation and comments.</p>
      </li>
      <li><strong>Refactoring Existing Code into OOP</strong>
        <p>How to reorganize procedural code into object-oriented structures.</p>
      </li>
    </ul>
    
    <h3>10. Review and Hands-On OOP Project</h3>
    <ul>
      <li><strong>Mini-Project: Build a Simple Animal Simulator</strong>
        <pre><code>class Animal:
    def __init__(self, name):
        self.name = name
    def speak(self):
        return f"{self.name} makes a noise."

class Dog(Animal):
    def speak(self):
        return f"{self.name} barks."

class Cat(Animal):
    def speak(self):
        return f"{self.name} meows."

animals = [Dog("Rex"), Cat("Whiskers")]
for animal in animals:
    print(animal.speak())
</code></pre>
      </li>
      <li><strong>Q&amp;A and Code Review Sessions</strong>
        <p>Discuss challenges and improvements.</p>
      </li>
      <li><strong>Peer Programming Exercises</strong>
        <p>Work in pairs to extend and improve your code.</p>
      </li>
      <li><strong>Final Recap of OOP Concepts</strong>
        <p>Review and summarize key ideas.</p>
      </li>
    </ul>