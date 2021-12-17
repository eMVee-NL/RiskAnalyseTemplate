# Risk Analyse Template

During a course in (ISC)² CSSLP, risk analyzes and their prioritization were discussed, among other things. One of the things is that it is often difficult to come to a conclusion about the impact and the probability of a risk. Partly on the basis of this combination, a risk could be prioritized in order to implement mitigating measures.

In the past, as a software tester, I often tested risk-based and I thought that I once built a similar template to simplify my work as a software tester. I have therefore put together a new version in Microsoft Excel. There is a VBA macro in it to prioritize the risks. So if you want to use this template you need to be able to run the macros. If you do not want this, you cannot use the tab in which the risks are prioritized.

Of course you can view the source code yourself to check or make adjustments. You could also sign the VBA macro yourself that you trust.

Obviously, I recommend looking at the source code before running anything from the internet. Viewing the source code can be done in MS Excel with the ```ALT``` + ```F11``` key combination.

## Usage

### Tab Information
When opening the file, the "Information" tab will open. A project or application name can be entered at the top.
On the left, names can be entered next to the roles. These are copied to the Risks tab so that they can enter a score per risk that is linked to their name.
![Alt text](/Screenshots/Tab%20-%2001%20-%20Information.png "Tab - Information")


### Tab Risk matrix
The "Risk matrix" tab indicates how risks can be classified based on impact and likelihood. Examples are given of impact in terms of costs or how often and quickly something can occur, for example. These may differ per organization. So feel free to adjust them to the values within your own organization. The matrix has been drawn up so that risks can be prioritized. Keep this tab in mind when running a risk analysis session so that you can use it as a resource.
![Alt text](/Screenshots/Tab%20-%2002%20-%20Risk%20matrix.png "Tab - Risk matrix")


### Tab Quality attributes
I have added the tab "Quality attributes" based on TMap® (Test Management Approach) in this document, because quality attributes can be tested with this method and test techniques. In this way, a certain risk or user story can be tested in a structured way in a project. This is beneficial to guarantee the quality of a system. This tab is for informational purposes only, so you can select a proper test technique.
![Alt text](/Screenshots/Tab%20-%2003%20-%20Quality%20attributes.png "Tab - Quality attributes")


### Tab Risks
In the "Risks" tab, risks can be entered with the associated cause and a possible consequence. Each participant can then enter a value for the impact and likelihood per risk. Based on this data, an average value is obtained for the risk classification. In this tab you can indicate which user story and which quality attribute can be associated with a risk.
![Alt text](/Screenshots/Tab%20-%2004%20-%20Risks.png "Tab - Risks")


### Tab Prioritized risks
The last tab "Prioritized risks" will initially be empty. On the right side of the tab is the "Prioritize risks" button. When clicked on this, the VBA code will place the risks in the correct order on this tab. A mitigating measure can also be included here and a residual risk can be indicated.
![Alt text](/Screenshots/Tab%20-%2005%20-%20Prioritzed%20risks.png "Tab - Prioritized risks")
