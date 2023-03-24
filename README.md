
Shiro 1.4.0 & Layui 2.5.4 permission management system.
Tool
Common Utils/Code Quality
guava : Guava is a set of core libraries that includes new collection types (such as multimap and multiset), immutable collections, a graph library, and utilities for concurrency, I/O, hashing, primitives, strings, and more.
p3c : Alibaba Java Coding Guidelines pmd implements and IDE plugin，Used to improve your programming specifications，This plugin is available on both Eclipse and IDEA and is recommended.
arthas : Arthas is a Java Diagnostic tool open sourced by Alibaba. Arthas allows developers to troubleshoot production issues for Java applications without modifying code or restarting servers.
sonarqube ：SonarQube empowers all developers to write cleaner and safer code.
checkstyle :Checkstyle is a development tool to help programmers write Java code that adheres to a coding standard. By default it supports the Google Java Style Guide and Sun Code Conventions, but is highly configurable. It can be invoked with an ANT task and a command line program.
pmd : An extensible multilanguage static code analyzer.
spotbugs : SpotBugs is FindBugs' successor. A tool for static analysis to look for bugs in Java code.
hutool : A set of tools that keep Java sweet.
Database
redisson ：Redisson - Redis Java client with features of In-Memory Data Grid. Supports over 30 objects and services: Set, Multimap, SortedSet, Map, List, Queue, Deque, Semaphore, Lock, AtomicLong, Map Reduce, Publish / Subscribe, Bloom filter, Spring Cache, Tomcat, Scheduler, JCache API, Hibernate, RPC. Introduction to the Redisson project.
Others
thingsboard : Open-source IoT Platform - Device management, data collection, processing and visualization.import java.util.Scanner;

public class AddTwoNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();

        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        int sum = num1 + num2;

        System.out.println("The sum of " + num1 + " and " + num2 + " is " + sum + ".");
    }
}
