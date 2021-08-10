#include <stdio.h>

int up_data[10] = {0x20,0x25,0x22,0x23,0x24,0x69};
int crc;
int main()
{
for(int i=0;i<5;i++)
{
    if(up_data[i]==0x20 & up_data[i+1]==0x25)
    {
        for(int j=2;j<5;j++)
        {
            crc += up_data[j];
            
        }
        if(crc == up_data[5])
        {
        printf("packet mached\n");
        }

        else
        {
            printf("Invalid packet");
        }
        break;
        
    }
    else
    {
        printf("packet not mached");
    }
}
    
}
