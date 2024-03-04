# gherg-
{
	char i, s[30];
	FILE * f;
	clrscr();
	f = fopen("DSSV.TXT", "w");
	i = 1;
	printf("Nhap ho ten cua tung hoc sinh, ket thuc go Enter\n");
	do {
{
	char i, s[30];
	FILE * f;
	clrscr();
	f = fopen("DSSV.TXT", "w");
	i = 1;
	printf("Nhap ho ten cua tung hoc sinh, ket thuc go Enter\n");
	do {
		printf("Ho ten hoc sinh thu %d : ", i++);
		gets(s);
		if (strlen(s) > 0)
		{
			strcat(s, "\n");
			fputs(s, f);
		}
	} while (strlen(s) > 0);
	fclose(f);
	clrscr();
		printf("Ho ten hoc sinh thu %d : ", i++);
		gets(s);
		if (strlen(s) > 0)
		{
			strcat(s, "\n");
			fputs(s, f);
		}
	} while (strlen(s) > 0);
	fclose(f);
	clrscr();
