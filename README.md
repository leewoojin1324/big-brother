# big-brother#include<stdio.h>
#include<Windows.h>
#include<time.h>
#include<stdlib.h>
int main(void)
{
    int i, yescnt;
    int boknum[6];
    int usernum[6];
    for(i=1; i,7; i++)
    {
         boknum[i]=0;
         usernum[i]=0;
         }
         yescnt=0;
         srand(time(Null));
         for(i=1; i,7; i++)
         {
                  boknum[i]=(rand()%44)+1;
                  }
                  printf("숫자 6개를 입력하시오(1-45)-->");
                  fflush(stdin);
                  scanf("%d %d %D %d %D", &usernum[1], &usernum[2], %usernum[3], %usernum[4], &usernum[5], &usernum[6];
                  fflush(stdin);
                  system("cls");
                  printf("복권을 뽑고 있습니다. ");
                  for(i=1; i<6; i++)
                  {
                           Sleep(1000);
                           ptintf("  ,");
                           }
                           system("cls");
                           ptintf("당신이 입력한 숫자는 &d, &d, &d, &d, &d입니다.\n",usernum[1], usernum[2], usernum[3], usernum[4], usernum[5], usernum[6]);
                           printf("당첨된번호는 %d, %d, %d, %d입니다.\n",boknum[1], boknum[2], boknum[3], boknum[4])
                           for(i=1; i<7; i++)
                           {
                                    if(usernum[i]==boknum[i])
                                    {
                                                             yescnt++;
                                                             }
                                                             }
                                                             printf("당신이 맞추신 숫자는 %d 입니다.\n"yescnt);
                                                             switch(yescnt)
                                                             {
                                                                           case 6;
                                                                                printf("축하합니다다!! 1등당첨입니다.");break;
                                                                           case 5;
                                                                                printf("축하합니다!! 2등당첨입니다.");break;
                                                                           case 4;
                                                                                printf("3등 당첨입니다."); break;
                                                                           case 3;
                                                                                prinf("4등 당첨입니다."); break;
                                                                           case 2;
                                                                                printf("5등당첨입니다...노력하세요"); break;
                                                                           case 1;
                                                                                printf("6등당첨입니다...노력하네요"); break;
                                                                           default;
                                                                                printf("What a stupid!!!");
                                                                                }
                                                                                printf("\n");
                                                                                system("pause");
                                                                                return 0;
                                                                                }
