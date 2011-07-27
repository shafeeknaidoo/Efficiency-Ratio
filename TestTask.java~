public class TestTask
{
	public void run()
	{/* 
		Task t = new Task(1,"task1","new description",8,3,10,"incomplete");
		Task t1 = new Task(1,"task1","new description",8,3,10,"incomplete");
		Task t2 = new Task(1,"task1","new description",8,3,10,"incomplete");
		
		double effiecienyRatio = t.calculateEfficencyRatio();
		double developerEffectiveness = t.calculateDeveloperEffectiveness(effiecienyRatio);
		t.printSummary(); */
		
		
		Task[] tasks = new Task[4];
		for(int i = 0; i < 4; i++)
		{
			tasks[i] =  new Task(i,"task1","new description",8,3,2,"incomplete");
		}
		//tasks[2].printSummary();
		
		System.out.println(Task.calculateGeneralEffieciencyRatio(tasks));
		
		System.out.println(Task.calculateGeneraldeveloperEffectiveness(tasks));
		
		
		System.out.println(Task.taskCounter);
		
	}
	
	public static void main(String[] args)
	{
		TestTask tpo = new TestTask();
		tpo.run();
		
	}
}
