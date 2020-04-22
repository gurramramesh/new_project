#include<iostream>
using namespacce std;

class vechile
{
        public:
                vechile()
                {
                std::cout<<"this is vehicle"<<endl;
                }
      virtual   void display()
                {
                        std::cout<<"this is vechile class"<<endl;
                }

};

class fourwheeler
{

        public:
                fourwheeler()
                {
                        std::cout<<"this is 4 wheeler"<<endl;
                }
                void display()
                {
                        std::cout<<"this is vechile class"<<endl;
                }


};

int main()
{
vechile v1;
fourwheeler f1;

f1.dispaly();

return 0;
}
