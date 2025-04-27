# info2680-061-project---rolodex-solved
**TO GET THIS SOLUTION VISIT:** [INFO2680-061 Project – Rolodex Solved](https://www.ankitcodinghub.com/product/info2680-061-project-rolodex-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;35591&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;INFO2680-061 Project - Rolodex Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Necessary skills: STL&nbsp;<em>container classes, iterators, algorithms, and stream I/O</em>

<strong>Description</strong>

This goal of this project is to build an information manager similar to a rolodex (see&nbsp;<a href="https://en.wikipedia.org/wiki/Rolodex">http://en.wikipedia.org/wiki/Rolodex</a>). A physical rolodex is made up of cards arranged in alphabetical order by [Last Name, First Name]. Each card contains some information, usually name, address, phone number and type of business (why the person is in the rolodex). The physical mechanism of using a rolodex is turning the group of cards and flipping through them. When the last card is read, the rolodex is then at the start of the list since a rolodex is built on a circular track.

<strong>Design Notes</strong>

For this project you’ll implement a&nbsp;<strong>Card</strong>&nbsp;class (in Card.h and Card.cpp), a&nbsp;<strong>Rolodex</strong>&nbsp;class (in Rolodex.h and Rolodex.cpp), and a&nbsp;<strong>main()</strong>&nbsp;function (in main.cpp). The code in main() reads interactive commands that perform actions on its Rolodex object (like add a card,&nbsp; search for a card,&nbsp; list the rolodex cards, etc).

The&nbsp;<strong>Card</strong>&nbsp;class is used to represent a single Rolodex card. This class has std::string data members for First name, Last name, Occupation, Address (entire address can be in one string), and Phone number.&nbsp; It has get/set&nbsp; member functions to allow getting and setting of the member data values (e.g. first name), and a&nbsp;<strong>show</strong>(ostream&amp; os) function that knows how to display the card on the supplied ostream parameter.&nbsp; This class does&nbsp;<em>not</em>&nbsp;know about Rolodex functionality, it just encapsulates a single card’s information.

The&nbsp;<strong>Rolodex</strong>&nbsp;class manages a collection of Card objects. It must have a data member that is an STL container class to hold the set of rolodex Card objects (i.e.&nbsp;<em>not</em>&nbsp;a C/C++ array, but an STL container like list, vector, multiset, etc), and an associated STL iterator object to reference the ‘current’ Card. The STL container used must be able to handle the case of duplicate names (e.g.&nbsp; two of Jim Smith, etc).&nbsp; The Rolodex member functions just manage the STL collection of Cards, and may have parameters or return values that are a Card object.&nbsp;The Rolodex class does&nbsp;<em>not</em>&nbsp;have code to read data for new cards, or printing Cards. Data input is done by code in main() and Card objects are passed into and out of the Rolodex object. Displaying cards is done by the Rolodex code calling the Card’s show() member function, passing an ostream for it to display on. Some of your Rolodex member functions might include the following :

<ul>
<li><strong>add</strong>(Card&amp; card) takes a Card object as a parameter (by ref is more efficient), adds it to the STL container member (in the appropriate spot&nbsp; so the cards are kept in alphabetical order by [last name, first name]), and sets it as the ‘current card’ in the Rolodex by setting the&nbsp;member&nbsp;STL iterator to point at the Card just added..</li>
<li><strong>remove</strong>() removes the current card from the Rolodex’s STL container, returns it, and makes the following card the ‘current’ card. If the last card in the STL container is removed, the ‘current’ card should be set to the first card in the container (i.e. wraps around).</li>
<li><strong>getCurrentCard</strong>() returns the current Card (actually, a copy of it).</li>
<li><strong>flip</strong>()&nbsp;updates the current card position to the next Card in the Rolodex’s STL container, and&nbsp;returns that Card. If at the last card in the container, it wraps around to the first card.</li>
<li><strong>search</strong>(const std::string&amp; lastname, const std::string&amp; firstname)&nbsp; finds the requested card and sets it as the current card and returns true indicating the search found a card.&nbsp;&nbsp;If no exact matching card is found, the current card position remains unchanged and false is returned.</li>
<li><strong>show</strong>(ostream&amp; os) takes an ostream as a parameter. It iterates through all the cards in the STL container from beginning to end, invoking each card’s show() method, and passing the ostream parameter. The Rolodex show() doesn’t do any actual output – it just iterates through the collection and requests each card to display its contents by calling its show() member function. The current card remains unchanged.</li>
</ul>
The&nbsp;<strong>main</strong>() function defines and loads the Rolodex object with the starting data (by adding a series of Cards to it), and then accepts&nbsp;<em>interactive</em>&nbsp;requests that act on the Rolodex. For each interactive command, main() invokes one or more member functions on the Rolodex object. For example, you might implement the interactive commands as follows:

<ul>
<li><strong>list</strong>&nbsp;– displays the entire rolodex. It calls the Rolodex’s show(…) function to display the all the rolodex cards..</li>
<li><strong>view</strong>&nbsp;–&nbsp;&nbsp;displays the card at the current position in the rolodex. It&nbsp;calls the&nbsp;Rolodex’s&nbsp;getCurrentCard() function, then calls show(…) on the returned Card.</li>
<li><strong>flip</strong>&nbsp;– updates the current roledex position to the next card, and displays it. Flipping past the last card wraps around to the first card. It&nbsp;calls the Rolodex’s flip() function to get the next Card, then calls show(…) on the returned Card.</li>
<li><strong>add</strong>&nbsp;– adds a new card to the rolodex. Prompts for each field value, reads them, and creates a new Card object&nbsp;with the information, then calls Rolodex’s add(…) function to add the new Card to the rolodex (which puts it in the correct position in its STL container).</li>
<li><strong>remove</strong>&nbsp;– removes the card at the current position. It first&nbsp;calls the Rolodex’s getCurrentCard() function , calls show(…) on the returned card to display it as part of the confirmation prompt, and if ‘yes’ is entered to remove it, it calls Rolodex’s remove() function to remove the Card from the rolodex.</li>
<li><strong>search</strong>&nbsp;– finds and displays a card.. This command prompts for the last name&nbsp;and first name to search for, then calls the Rolodex’s search(..) function. If a matching card is found, it then calls the Rolodex’s getCurrentCard() function to get it, and then calls show() to display it.&nbsp; If no matching card is found, it displays “card not found”.</li>
<li><strong>quit</strong>&nbsp;– exits the program.</li>
</ul>
Note that some of the command processing code in main() requires several steps (like the add, remove, and search commands) and may invoke several member functions on the Rolodex to complete a command. This keeps the Rolodex implementation *minimal*, and the Rolodex class doesn’t do any of the prompting, input, output, etc. The Rolodex class has basic functionality to manage the collection of Rolodex cards (which is a better design).&nbsp; The Rolodex class just maintains the collection of cards (in order), and provides functionality to add, remove, search for and get cards, list the collection of cards, maintains a ‘current’ card position, and can move the position to the next card. Specific output formatting, data entry, etc., is outside of the Rolodex class. When starting a class design, keep it as small as possible – it’s always easier to add a new member function when there’s a proven need, vs. trying to remove functions after the class is in use..

The Rolodex class must be able to handle the cases of adding or removing a card to the beginning or end of the collection, and ‘wrapping around’ from the end to the beginning of the collection when moving forward from the last card to the first card.

The Standard Library std::string class should be used for the character information (no char* or char arrays).

<strong>Test Data</strong>

Use the following information to provide the initial information to demonstrate the functionality of your rolodex program. You can hardcode these entries into your rolodex initialization in main() to simulate reading the information from a file, or optionally read them from a file. The address can be a single string value (no need to split into street, city, state, zip).

<table>
<tbody>
<tr>
<td><strong>First:</strong></td>
<td><strong>Last:</strong></td>
<td><strong>Occupation:</strong></td>
<td><strong>Address:</strong></td>
<td><strong>Phone:</strong></td>
</tr>
<tr>
<td>Tony</td>
<td>Hansen</td>
<td>Writer</td>
<td>12 E. St. NY, NY 33333</td>
<td>555-9999</td>
</tr>
<tr>
<td>Jon</td>
<td>Smyth</td>
<td>Computer Hardware</td>
<td>CMU

Computer Services

Pittsburgh, PA</td>
<td>555-1324</td>
</tr>
<tr>
<td>Alonza</td>
<td>Heard</td>
<td>Mechanic</td>
<td>123 Anyplace Ave

Malden, MA</td>
<td>555-5678</td>
</tr>
<tr>
<td>Jen</td>
<td>Reyes</td>
<td>Graphic artist</td>
<td>325 Oak Rd

Wilmington, MA</td>
<td>555-4950</td>
</tr>
<tr>
<td>Alan</td>
<td>Lupine</td>
<td>Vet</td>
<td>1 Bigelow Ave.

Lawrence, MA</td>
<td>555-7654</td>
</tr>
<tr>
<td>Jewel</td>
<td>Proverb</td>
<td>Landscaper</td>
<td>34 Washington St.

Waltham, MA</td>
<td>555-3333</td>
</tr>
<tr>
<td>Paul</td>
<td>Revere</td>
<td>Radical Revolutionary</td>
<td>45 Commonwealth Ave.

Boston, MA</td>
<td>555-1776</td>
</tr>
<tr>
<td>Adolf</td>
<td>Coors</td>
<td>Beer Manufacturer</td>
<td>Boston MA</td>
<td>555-2337</td>
</tr>
<tr>
<td>Seymour</td>
<td>Papert</td>
<td>Lego Professor</td>
<td>MIT</td>
<td>555-1111</td>
</tr>
<tr>
<td>Fred</td>
<td>Milton</td>
<td>Sales</td>
<td>12 Freedom Way

Nashua, NH</td>
<td>&nbsp;555-9981</td>
</tr>
</tbody>
</table>
<strong>Test Steps</strong>

Test your program with the following sequence of actions:

<ul>
<li>list the rolodex</li>
<li>search for Alonza Heard</li>
<li>view the current card (should be Alonza Heard)</li>
<li>flip to the next card (should be&nbsp; Alan Lupine)</li>
<li>search for Jon Smyth</li>
<li>view the current card (should be Jon Smyth)</li>
<li>remove Jon Smyth</li>
<li>view the current card (should be Adolf Coors, ie. wrapped from the end to the beginning)</li>
<li>add Matthew Williams, Teacher, 69 Main St, Acton, MA,&nbsp; 555-9330</li>
<li>view the current card (should be Matthew Williams)</li>
<li>flip to the next card (should be Adolf Coors)</li>
<li>remove Adolf Coors</li>
<li>view the current card (should be Tony Hanson)</li>
<li>add Jim Butler, Contractor, 33 Cedar Lane, Concord, MA, 555-8535</li>
<li>view the current card (should be Jim Butler)</li>
<li>search forJewel Proverb</li>
<li>view the current card (should be Jewel Proverb)</li>
<li>remove Jewel Proverb</li>
<li>view the current card (should be Paul Revere)</li>
<li>add&nbsp;<em>another</em>&nbsp;Jim Butler, Consultant, 22 Minuteman St, Lexington, MA.&nbsp; 555-4422</li>
<li>add Dan Butler, Chauffeur, 68 Willow St, Westford, MA, 555-8493 (should sort&nbsp;<em>before</em>&nbsp;the Jim Butler cards)</li>
<li>list the rolodex</li>
<li></li>
</ul>
Since there is a lot of runtime output for this project, you may need to increase the buffer size of your Command Prompt window in order to retain all of it.&nbsp; Do the following:

<ul>
<li>Click on the&nbsp;&nbsp;<strong>C:\</strong>&nbsp; icon on the top left of the window’s title bar</li>
<li>Click on ‘Properties’ in the pop up menu</li>
<li>Click on the ‘Layout’ tab.</li>
<li>For the Height setting in ‘Screen Buffer Size’, choose a large value (like 1000)</li>
<li>Click on the ‘Options’ tab.</li>
<li>Select and check the “QuickEdit mode” in Edit Options (allows selecting text in the window and hit Enter to copy to clipboard)</li>
<li>Click Ok.</li>
<li>Select “Modify shortcut that started this window”, and click Ok.</li>
</ul>
You can optionally use a file of ‘interactive’ commands to perform the specified test steps,&nbsp; so that you don’t need to repeatedly enter the same data from the keyboard as you test your program.. Either way, main() is driven by a set of entered commands, and does&nbsp;<strong>not</strong>&nbsp;have the above test steps hardcoded.

&nbsp;

&nbsp;

— Starting Rolodex data&nbsp; —

&nbsp;

Code for main() to initialize the Rolodex:

&nbsp;

Rolodex rolo;

&nbsp;

// initial information for Rolodex

rolo.add(Card(“Tony”, “Hansen”, “Writer”, “12 E. St. NY, NY 33333”, “555-9999”));

rolo.add(Card(“Jon”, “Smyth”, “Computer Hardware”, “CMU Computer Services Pittsburgh, PA”, “555-1324”));

rolo.add(Card(“Alonza”, “Heard”, “Mechanic”,&nbsp; “123 Anyplace Ave Malden, MA”, “555-5678”));

rolo.add(Card(“Jen”, “Reyes”, “Graphic artist”, “325 Oak Rd Wilmington, MA”, “555-4950”));

rolo.add(Card(“Alan”, “Lupine”, “Vet”, “1 Bigelow Ave. Lawrence, MA”, “555-7654”));

rolo.add(Card(“Jewel”, “Proverb”, “Landscaper”, “34 Washington St. Waltham, MA”, “555-3333”));

rolo.add(Card(“Paul”, “Revere”, “Radical Revolutionary”, “45 Commonwealth Ave. Boston, MA”, “555-1776”));

rolo.add(Card(“Adolf”, “Coors”, “Beer Manufacturer”, “Boston MA”, “555-2337”));

rolo.add(Card(“Seymour”, “Papert”, “Lego Professor”, “MIT”, “555-1111”));

rolo.add(Card(“Fred”, “Milton”,&nbsp;&nbsp; “Sales”, “12 Freedom Way Nashua, NH”, “555-9981”));

&nbsp;

or if you want to read from a file:

&nbsp;

Tony Hansen

Writer

12 E. St. NY, NY 33333

555-9999

&nbsp;

Jon Smyth

Computer Hardware

CMU Computer Services, Pittsburgh, PA

555-1324

&nbsp;

Alonza Heard

Mechanic

123 Anyplace Ave, Malden, MA

555-5678

&nbsp;

Jen Reyes

Graphic artist

325 Oak Rd, Wilmington, MA

555-4950

&nbsp;

Alan Lupine

Vet

1 Bigelow Ave., Lawrence, MA

555-7654

&nbsp;

Jewel Proverb

Landscaper

34 Washington St. Waltham, MA

555-3333

&nbsp;

Paul Revere

Radical Revolutionary

45 Commonwealth Ave., Boston, MA

555-1776

&nbsp;

Adolf Coors

Beer Manufacturer

Boston MA

555-2337

&nbsp;

Seymour Papert

Lego Professor

MIT

555-1111

&nbsp;

Fred Milton

Sales

12 Freedom Way, Nashua, NH

555-9981

&nbsp;

&nbsp;
