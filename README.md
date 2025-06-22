# Queue-Interface-in-JAVA
package collectionframwork;
import java.util.*;
public class QueueInterface {
    static void QueueExamples(){
        LinkedList<Integer> q= new LinkedList<>();
        q.offer(1);
        q.offer(2);
        q.offer(3 );
        System.out.println(q);
        System.out.println(q.peek()); // 1
        System.out.println(q.poll()); // will also remove 1
        System.out.println(q.peek()); // 2
        System.out.println(q.isEmpty());
        System.out.println(q.size());
        System.out.println(q);
    }

    public static void main(String[] args) {
        QueueExamples();

    }
}
