# SinglyLinkedList-DSA-

import java.util.*;
class Node{
    int data;
    Node next;
    Node(int data){
        this.data= data;
        this.next = null;
    }
}
class SinglyLinkedList{
    Node head;
    public void InsertAtbegin(int data){
        Node newnode = new Node(data);
        newnode.next = head;
        head = newnode;
    }
    public void InsertAtend(int data){
        Node newnode = new Node(data);
        Node temp = head;
        while(temp.next!=null){
            temp = temp.next;
        }
        temp.next= newnode;
        
    }
    public void InsertAtposition(int data,int position){
        if(position<=0){
            System.out.println("Invalid Position");
            return;
        }
        if(position==1){
            Node newnode = new Node(data);
            for(int i=0;i<position-1;i++){
                
            }
        }
    }
    
    
    public void DeleteEnd(){
        if(head==null){
            System.out.println("No need to delete");
        }
        if(head.next==null){
            head = null;
            return;
        }
        Node temp = head;
        while(temp.next!=null&&temp.next.next!=null){
            temp=temp.next;
        }
        temp.next=null;
    }
    public void DeleteBegin(){
        if(head==null){
            System.out.println("No need to delete");
        }
        else{
            head = head.next;
        }
        
    }
    
    public void display(){
        Node temp = head;
        while(temp!=null){
            System.out.println(temp.data + " ");
            temp=temp.next;
        }
        System.out.println();
        
    }
}
public class Main{
    public static void main(String[] args){
        SinglyLinkedList list = new SinglyLinkedList();
        list.InsertAtbegin(11);
        list.InsertAtbegin(22);
        list.InsertAtbegin(33);
        list.InsertAtbegin(44);
        list.InsertAtend(99);
        list.InsertAtend(100);
        list.display();
        list.DeleteEnd();
        list.display();
        list.DeleteBegin();
        list.display();
        
    }
}

