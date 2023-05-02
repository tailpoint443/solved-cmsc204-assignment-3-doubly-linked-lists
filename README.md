Download Link: https://assignmentchef.com/product/solved-cmsc204-assignment-3-doubly-linked-lists
<br>
Your assignment is to write a generic doubly-linked list class with and iterator and a generic sorted doubly-linked list class with an iterator that inherits from your generic doubly-linked class. The GUI has been provided for you for this assignment to help you visualize your doubly-linked list. Your list classes will also be tested with Junit tests.




Exception handling

Generic Classes

Doubly Linked List

Ordered Doubly Linked List

Iterators

Comparators




<strong>BasicDoubleLinkedList</strong>




This generic doubly-linked list relies on a head (reference to first element of the list) and tail (reference to the last element of the list). Both are set to null when the list is empty. Both point to the same element when there is only one element in the list. A node structure has only three fields: data and the prev and next references. The class must only define the following entities: an inner class Node, an inner class that implements ListIterator (for the iterator method), head and tail references and an integer representing the list size. However only the next(), hasNext(), previous() and hasPrevious() methods of the ListIterator are you required to implement.  The rest of the methods can throw the UnsupportedOperationException, such as:

public void remove() throws UnsupportedOperationException{

throw new UnsupportedOperationException();}

All the entities are defined as protected so they can be accessed by the subclass.  Follow the Javadoc that is provided.




<strong>SortedDoubleLinkedList</strong>

A generic sorted doubly-linked list will be constructed using a provided Comparator to determine how the list is to be sorted.  It extends BasicDoubleLinkedList class.  The <strong>addToFront</strong> and the <strong>addToEnd </strong>methods will not be supported and an <strong>add</strong> method will be added that inserts to the doubly-linked list in sorted order dependent on the Comparator. Follow the Javadoc that is provided.




<strong>Exception Handling</strong>

<ul>

 <li>UnsupportedOperationException – this exception is a Java library exception and will be returned by the addtoFront and addToEnd implementations of the SortedLinkedList class and by the remove method of the iterator.</li>

 <li>NoSuchElementException – this exception is a Java library exception and will be returned by the next function within the iterator class when there are no more elements in the linked list.</li>

</ul>




<strong>GUI driver (provided for you)</strong>

<strong>          </strong>A GUI driver has been provided for you to help you visualize your doubly-linked lists. Here is the minimum that must be in place to start using the GUI driver effectively.

<ul>

 <li>All methods in your BasicDoubleLinkedList and SortedDoubleLinkedList must be stubbed.</li>

 <li>The <strong>addToFront</strong> or <strong>addToEnd</strong> method of the BasicDoubleLinkedList must be implemented to create a basic doubly-linked list.</li>

 <li>The <strong>add</strong> method of the SortedDoubleLinkedList must be implemented to create a sorted doubly-linked list.</li>

 <li>The <strong>toArrayList</strong> method in both the BasicDoubleLinkedList and SortedDoubleLinkedList, which returns an arraylist of the items in the list from the head of list to the tail of list. This method is used to display the contents of the lists.</li>

</ul>




<strong>Testing</strong>

<ol>

 <li>Create a JUnit Test – BasicDoubleLinkedListTest_STUDENT.</li>

 <li>Create a JUnit Test – SortedDoubleLinkedListTest_STUDENT.</li>

</ol>

Adding to a Basic List                                                                                   Adding to a Sorted List

Removing Second from basic                                               Removing Thomas from sorted

<table>

 <tbody>

  <tr>

   <td width="54"></td>

   <td width="51"></td>

   <td width="352"></td>

   <td width="51"></td>

  </tr>

  <tr>

   <td></td>

   <td rowspan="2"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>




Start the iterators for Basic and Sorted. Think of iterators being “in between” nodes.




<table>

 <tbody>

  <tr>

   <td width="64"></td>

   <td width="47"></td>

   <td width="174"></td>

   <td width="47"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>









































































Example of selecting “Next” for Basic and then for Sorted list. Think of iterators being “in between” nodes.

<table>

 <tbody>

  <tr>

   <td width="41"></td>

   <td width="42"></td>

   <td width="7"></td>

   <td width="61"></td>

   <td width="89"></td>

   <td width="42"></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="4"></td>

   <td rowspan="2"></td>

  </tr>

  <tr>

   <td></td>

   <td rowspan="2"></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>

Example of “Next” for basic and “Previous” for Sorted. Think of iterators being “in between” nodes.

<strong><u>Deliverables / Submissions</u></strong><strong>: </strong>

<u>Design</u>: UML class diagram with algorithm (pseudo-code) for methods

<u>Implementation</u>: Submit a compressed file containing the follow (see below):  The Java application (it must compile and run correctly); Javadoc files <strong>in a directory</strong>; a write-up as specified below.  Be sure to review the provided project rubric to understand project expectations.  The write-up will include:

<ul>

 <li>Final design: UML diagram with pseudo-code</li>

 <li>In three or more paragraphs, highlights of your learning experience</li>

</ul>




<strong><u>Deliverable format</u></strong><strong>:</strong> The above deliverables will be packaged as follows. Two compressed files in the following formats:

<ul>

 <li>zip, a compressed file in the zip format, with the following:

  <ul>

   <li>Write up (Word document) – reflection paragraphs</li>

   <li>UML Diagram – latest version (Word or jpg document)</li>

   <li>doc (directory) – Javadoc</li>

  </ul></li>

</ul>

<ul>

 <li style="list-style-type: none;">

  <ul>

   <li style="list-style-type: none;">

    <ul>

     <li style="list-style-type: none;">

      <ul>

       <li>File1.html (example)</li>

       <li>File2.html (example)</li>

       <li>Sub-directory (example)</li>

      </ul></li>

    </ul></li>

  </ul></li>

</ul>

<ul>

 <li>src (directory)</li>

</ul>

<ul>

 <li style="list-style-type: none;">

  <ul>

   <li style="list-style-type: none;">

    <ul>

     <li style="list-style-type: none;">

      <ul>

       <li>File1.java (example)</li>

       <li>File2.java (example)</li>

      </ul></li>

    </ul></li>

  </ul></li>

</ul>




<ul>

 <li>zip, a compressed file containing one or more Java files:

  <ul>

   <li>java (example)</li>

   <li>java (example)</li>

  </ul></li>

</ul>

This folder should contain Java source files only


