# Mappings

leader key		,

# Files

|Command				   	|	Key  |
|---------------------------|--------|
|NerdTree				   	| F12    |
|Toggle					   	| F3     |
|Ctrl+P                    	|        |
|	Open					|<Ctrl+P>|
|	cycle beteewn modes		|<Ctrl+f>|
|	go to functions			|,fu|
|	mark files				|<Ctrl+z>|
|	opem marked files		|<Ctrl+o>|
|	clear cache				|F5|
|	open file in a vsplit	|<Ctrl+v>|
|	open file in a split	|<Ctrl+x>|
|set work dir				|,.      |
|Open in current dir		|,e      |
|Open in tab				|,te     |

# Search

	grep					,f
	clean search			<Ctrl+l> 
							,<space>
	fast move				,,gE
		char right			,,f	
		char left			,,F
		before right char	,,t
		after left char		,,T
		beggin of work		,,w
		beggin of workd b	,,b
		search char			,,s
		end work			,,e
							
# Window

split h					,h
split v					,v

# Buffers
previous buffer			,z
next buffer				,x
buffer close			,co

# Tabs
Next					<Tab>
Prev					<S-Tab>
new						<S-t>
	
# Edition

delete current workd	diw
delete within parens	di(
delele within "			di"
remove trailing spaces	,S
copy to clipboard		,y
copy current line		,yy
paste from clipboard	,p
paste from reg num		,<number>
set paste 				F11
Show undo history		F2
select up to )			vt)
select before )			vT(

# Code				

goto assignments		,g
goto definition			,d
call signature			0
documentation			K
usages					,n
rename					,r
comment a line			gcc
completions				<Ctrl+space>
ultisnips
	activate snippet		snippet name + <Tab>
	forward					<Ctrl+j>
	backward				<Ctrl+k>
Surround
	Change surround char	cs'
							cs"
							cs<char/s>
	Delete surround char	ds'
							ds"
	Surround work			ysiw<char>
Tagbar Toogle			F4
Close quickfix window	,cw
Fold selection			,zf
unfold					,za
emmet html macros
	activate			<Ctrl+y>,
	sample				div>p#foo$*3>a
	surround			visual select+ activate
	balance tag			<Ctrl+y>d
						<Ctrl+y>D
	next edit point		<Ctrl+y>n
	previosus			<Ctrl+y>N
	update image size	<Ctrl+y>i (on inmage tag)
	remove tag			<Ctrl+y>k
	toggle comment		<Ctrl+y>/
	make anchor			<Ctrl+y>a

#Utils

vim shell				,sh
show registers			,re

