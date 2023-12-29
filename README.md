# Cursor-Linked-Stack
## implementation of cursor linked stack that read a specific structured file(and checked iv valid) to compute postfix and prefix equations and convert between them.
file looks like :

<242>
	<section>
		<infix>
			<equation>5 + 30</equation>
			<equation>5 + 3 * 4.5</equation>
			<equation>( 15 + 3 ) * ( 4 ^ 2 )</equation>
		</infix>
                <postfix>
			<equation>2 30 4 * + <\equation>
			<equation>3 4 * 2 5 * + <\equation>
			<equation>12 3 - 4 + 5 6 * - <\equation>
			<equation>2.5 3 - 4 + 5 6 7 * + * <\equation>
                </postfix>
	<section>
</242>
