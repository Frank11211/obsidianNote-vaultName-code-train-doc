

<h4>Flow of Git</h4>
- Similar like Theme Park Entrance System 
- Reference as below 
![[Pasted image 20260330160159.png]]





-------------------------------------------------------------------------
<h1> Basic </h1>
<h5>Specify name & Email -- First time ONLY</h5> 
<table>
	<!-- Header format -->
	<tr>
		<th><h4>Command </h4></th>
		<th><h4>Explanation</h4></th>
	<tr>
	<tr>
		<td>git config --global user-name &lt;your_name&gt;</td>
		<td>Register account **NAME**</td>
	<tr>
	<tr>
		<td>git config --global user-name &lt;your_email&gt;</td>
		<td>Register account **E-mail**</td>
	<tr>
</table>

<h5>Set default branch </h5>
<table>
	<!-- Header format -->
	<tr>
		<th><h4>Command </h4></th>
		<th><h4>Explanation</h4></th>
	<tr>
	<tr>
		<td>git config --global inti default main</td>
		<td>set targeted branch as default</td>
	<tr>
</table>

<h5>Special File</h5>
<table>
	<!-- Header format -->
	<tr>
		<th><h4>Command </h4></th>
		<th><h4>Explanation</h4></th>
	<tr>
	<tr>
		<th>.gitignore</th>
		<th> Specify file that doesn't want to commit or Other Action</th>
	<tr>
</table>

<h5>Git command - Common use</h5>
<table>
	<!-- Header format -->
	<tr>
		<th><h4>Command </h4></th>
		<th><h4>Explanation</h4></th>
	<tr>
	<tr>
		<td>git status</td>
		<td>Check current status of Git</td>
	<tr>
	<tr>
		<td>git add &lt;specific_file_name&gt;</td>
		<td>add untrack file into git</td>
	<tr>
		<tr>
		<td>git add .</td>
		<td>add ALL untrack file</td>
	<tr>
	<tr>
		<td>git commit -m "msg with double quote"</td>
		<td>a "check point" of your repository</td>
	<tr>
	<tr>
		<td>git rm --cached &lt;file_name&gt;</td>
		<td>untrack / unstage the file into git</td>
	<tr>
</table>


<h5>Git command - Branching</h5>
<table>
	<!-- Header format -->
	<tr>
		<th><h4>Command </h4></th>
		<th><h4>Explanation</h4></th>
	<tr>
	<tr>
		<td>git branch</td>
		<td>list all branch</td>
	<tr>
	<tr>
		<td>git branch &lt;data_type&gt;</td>
		<td>new branch base name </td>
	<tr>
	<tr>
		<td>git switch</td>
		<td>Switch between branch</td>
	<tr>
	<tr>
		<td>git merge</td>
		<td>Combine between branch</td>
	<tr>
	<tr>
		<td>git branch -d &lt;branch_name&gt;</td>
		<td>delete branch base name</td>
	<tr>
	<tr>
		<td>git switch -d &lt;branch_name&gt;</td>
		<td>create & switch to branch</td>
	<tr>

</table>

<h4>Tips for Good Commit message</h4>
1. Keep Subject concise ( 简洁 )
2. Explain context & reason behind 
3. Separate subject from body with line.
4. =={red}**DO NOT**== 
	- Explain OVER detail in title , will cause overwhelm
	- Expect other's able to INSTANTLY understand.
My Example
- `<content_type> : <content>`
- feature : add a window for Signup & Login UI, available user signup or login their account.

----------------------------------------------
<h1> Intermediate </h1>

GitHub Web Panel -  **Anchors** to remember 

- **The Code Tab --- your home base**
	- Click **Branch Selector** ( usually says `main` or `master`)
		- top left of the Switch views between different branches

- **The "Pull Request" Tab** 
	- place propose "**merging**" -  combine sub-branch into your main branch 
	
![[Pasted image 20260330115834.png]]

**Tips:**  if see a yellow bar saying "Branch recently pushed" -- GitHub's shortcut to create a PR 

- **Insights -> Network** 
	- Show a visual graph of all your branches & how they connect ( or don't connect ).
	- Image show how to navigate to Insi
	
![[Pasted image 20260330115712.png]]

<h1>Website Resource Link :- </h1>
- https://ohmygit.org/  => Learn Git by Playing Game, but needed to download application first 
- https://learn.github.com/skills => Learn Git with actual GitHub