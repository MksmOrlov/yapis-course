## Идентификатор

объектно_ориентированный_язык_программирования (eng: object_oriented_programming_language)

## Определение

Объектно-ориентированный язык программирования - императивный язык программирования, который поддерживает представление программы в виде совокупности объектов, каждый из которых является экземпляром определенного класса, а классы образуют иерархию наследования.

## Пояснение

В центре ООП находится понятие объекта. Объект — это сущность, которой можно посылать сообщения и которая может на них реагировать, используя свои данные. Объект — это экземпляр класса. Данные объекта скрыты от остальной программы.

## Пример

Имплементация связного списка на Java

~~~Java
class LinkedList {
	private static Node head;
	private static int numNodes;
	
	public LinkedList(Object dat) {
		head = new Node(dat);
	}
	
	public void addAtHead(Object dat) {
		Node temp = head;
		head = new Node(dat);
		head.next = temp;
		numNodes++;
	}
	
	public void addAtTail(Object dat) {
		Node temp = head;
		while(temp.next != null) temp = temp.next; 
		temp.next = new Node(dat);
		numNodes++;
	}
	
	public void addAtIndex(int index, Node node) {
		Node temp = head;
		Node holder;
		for(int i=0; i < index-1 && temp.next != null; i++) temp = temp.next;
		holder = temp.next;
		temp.next = node;
		temp.next.next = holder;
		numNodes++;
	}
	
	public void deleteAtIndex(int index) {
		Node temp = head;
		for(int i=0; i< index - 1 && temp.next != null; i++) temp = temp.next;
		temp.next = temp.next.next;
		numNodes--;
	}
	
	class Node {
		private Node next;
		private Object data;
		
		public Node(Object dat) {
			data = dat;
		}
		
		public Object getData() {
			return data;
		}
	}
}
~~~

## Связь с другими понятиями

1. язык_программирования
2. императивный_язык_программирования

## Библиография

1. Grady Booch. Object-Oriented Analysis and Design with Applications.
