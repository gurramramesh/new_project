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

class twowheeler:public vechile
{

        public:
                twowheeler()
                {
                        std::cout<<"this is 2 wheeler"<<endl;
                }
                void display()
                {
                        std::cout<<"this is vechile class"<<endl;
                }

class fourwheeler:private vechile
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
twowheeler t1;

t1.display();
f1.dispaly();

return 0;
}
